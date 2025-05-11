
# 🧠 MISP Decaying Model Lab

This lab demonstrates how to configure and use **decaying models** in MISP (Malware Information Sharing Platform) to prioritize or age out threat intelligence indicators over time. This feature helps determine the relevance of an IOC based on its age and usage context.

## 🔧 Step-by-Step Configuration

### ✅ Step 1: Accessing Decaying Models Tool
Navigate to `Decaying Models Tool` under the MISP interface. From here, you can enable or disable specific attribute types and models.

![Decaying Models Tool](screenshots/misp-decayingmodel.png)

### 🔍 Step 2: Simulating a Model
Adjust the polynomial decay function parameters like **Lifetime**, **Decay Speed**, and **Cutoff Threshold** to simulate how the IOC score decays over time.

![Decay Curve Simulation](screenshots/misp-polynomial.png)

### 🧩 Step 3: Enable decaying model 
Selec NIDS simple decaying model and clock on the play button.

![Available Decaying Models](screenshots/misp-denable-decaying.png)

### 🔬 Step 4: Viewing Applied Decay Scores
Once configured, view the decayed score of various indicators on the Event page. This helps assess current threat relevancy.

![Decay Scores in Events](screeshots/misp-decaying-result.png)


## ✅ Outcome
This lab showcases how decay scoring can help automate IOC relevancy and improve the efficiency of your threat intelligence workflows.
