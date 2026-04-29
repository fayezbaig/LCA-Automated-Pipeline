# Note

No data confidential to Fraunhofer ISE is being used in this repository.

This repository contains only the scripts and workflow structure used for updating the ecoinvent database. All proprietary datasets, XML files, confidential outputs, and internal Fraunhofer ISE packages are excluded from this repository.

The original data, generated results, and supporting packages used during the actual project are confidential to Fraunhofer ISE and are therefore not included.

---

# Project Workflow

## Step 1: Updating the ecoinvent Database using Level 1 Flows

A script was created to update the ecoinvent database using the Level 1 flow data provided by the Fraunhofer supervisor.

This step focuses on processing the provided Level 1 flow information and integrating it into the ecoinvent database structure.

---

## Step 2: Updating the ecoinvent Database using Level 2 + Level 3 Flows

A second script was developed to update the ecoinvent database using Level 2 and Level 3 flows.

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

The internal packages developed and used to perform these operations are also confidential to Fraunhofer ISE and are not included in this repository.
