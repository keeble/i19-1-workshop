---
marp: true
theme: rose-pine
size: 16:9
backgroundImage: url('../assets/dls_blue.png')
style: |
  h1 {
    font-size: 4rem;
  }
  h2 {
     font-size: 2.2rem; 
  }
  h3 {
    font-size: 1.8rem;
  }
  p {
    font-size: 1.6rem;
    }
  li {
    font-size: 1.6rem;
    color: var(--text);
  }
---
# An introduction to ISPyB
![bg opacity](https://yhatt-marp-cli-example.netlify.com/assets/gradient.jpg)
Dean Keeble
I19 EH-1 Remote Users Workshop February 2023

---
## What is ISPyB and why do we need it?

![h:500px ](https://github.com/keeble/i19-1-workshop/raw/main/assets/ispyb_dc_graph.png)

---
## And that's just the data collection
- What _is_ this sample?
- Where did it come from?
- Whose is it?
- What did the results look like?

---
### ISPyB is:
:white_check_mark: a stable, efficient database supporting many beamlines at Diamond

### ISPyB is not:
:o: specifically made for small molecule crystallography

---
## Process Overview
![h:300px ](https://github.com/keeble/i19-1-workshop/raw/main/assets/workflow.drawio.svg)
#### https://www.diamond.ac.uk/Instruments/Crystallography/I19/Manual/EH1.html



--- 
## Step 1: Add Sample(s) to ERA
![bg right w:640px](https://www.diamond.ac.uk/dam/jcr:4cb1663c-ecd5-4096-8eb5-4148bed469ba/UASAcronym.2021-10-19-10-54-09.png)
1. uas.diamond.ac.uk
2. Add your samples to the ERA as usual
3. Add an acronym

---
## Step 1a: Wait for ERA to be validated
## (_...and then 3 hours more )_

---
## A couple of definitions
![w:1200](https://github.com/keeble/i19-1-workshop/raw/main/assets/christmas.drawio.svg)

---
## Step 2: Create the Shipment
1. ispyb.diamond.ac.uk
2. Log in and find the relevant proposal
3. Create a _Lab Contact_

---
<!--
<style scoped>
li {
   font-size:  1.2rem;
}
</style>
-->
### 2a: Create a lab contact
![bg left w:640px](https://www.diamond.ac.uk/dam/jcr:84c8c57b-a985-4ab4-ae7e-a3eab05e0cb8/VisitMenu-LabContact.2021-10-19-10-54-09.png)

The lab contact is the name and address of the person sending the samples to Diamond

---
### 2a:Create a lab contact
![bg left w:650px](https://www.diamond.ac.uk/dam/jcr:1d411fa3-56ed-43e3-9a6d-f2b2639eb229/LabContact-details1.2021-10-19-10-54-09.png)

The lab contact is the name and address of the person sending the samples to Diamond

---
## 2b: Register Dewars

---
## 2c: Create Shipment

---
## Step 3: Add Samples to Shipment

---
## 3a: Create Container

---
## 3b: Put samples in Container

---
# <!--fit--> Ship it
![bg opacity](https://github.com/keeble/i19-1-workshop/raw/main/assets/ship-it.webp)

---
# Using ISPyB during your experiment
![bg opacity](https://yhatt-marp-cli-example.netlify.com/assets/gradient.jpg)

---
During the visit you can see what's going on
![w:800](https://github.com/keeble/i19-1-workshop/raw/main/assets/webcams.png)

---
## Data Collections Page, the distl plot

---
## The concept of a data collection group

---
## the reciprocal lattice viewer

---
## Processing Summary

--- 
## Processing Outputs

---
## Imminent Improvements
There are some improvements coming soon which should hopefully make ispyb _even more useful_ :+1:
- Use the supplied formula in shelxt solve
- Attach shelxt outputs correctly as processing outputs


