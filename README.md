# Note

The scripts, data, internal packages, and generated outputs related to this project are confidential to Fraunhofer ISE and are therefore not included in this repository.

This repository is intended only to explain the scripts that were developed during the project, their purpose, and the overall workflow used for updating the ecoinvent database.

All automation and workflow implementation for this project were performed using Python and Brightway2.

No confidential Fraunhofer ISE data, scripts, XML files, proprietary packages, or internal results are being shared in this repository.

---

# Project Workflow

## Step 1: Updating the ecoinvent Database using Level 1 Flows

A script was developed using Python and Brightway2 to update the ecoinvent database using the Level 1 flow data provided by the Fraunhofer supervisor.

The purpose of this script was to process the provided Level 1 flow information and integrate it into the ecoinvent database structure.

---

## Step 2: Updating the ecoinvent Database using Level 2 + Level 3 Flows

A second script was developed using Python and Brightway2 to update the ecoinvent database using Level 2 and Level 3 flows.

This process consists of the following 5 steps:

### Step 1: Data Extraction from XML Files

Extract data from XML files provided by the supervisor.

### Step 2: Compute Allocation Factor

Calculate the allocation factor based on the extracted results.

### Step 3: Inventory Data Extraction after LCA

Perform Life Cycle Assessment (LCA) using the results from Step 2 and extract the required inventory data.

### Step 4: Perform Additional Calculations

Carry out the necessary supporting calculations required before final database integration.

### Step 5: Upload Data into the ecoinvent Database

Upload the final processed data into the ecoinvent database.

---

# Additional Note

The supporting packages developed and used to perform these operations are also confidential to Fraunhofer ISE and are not included in this repository.
