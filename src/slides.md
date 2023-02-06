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
    font-size: 1.5rem;
    }
  li {
    font-size: 1.5rem;
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
### 2a: Create a lab contact
![bg left w:650px](https://www.diamond.ac.uk/dam/jcr:1d411fa3-56ed-43e3-9a6d-f2b2639eb229/LabContact-details1.2021-10-19-10-54-09.png)

The lab contact is the name and address of the person sending the samples to Diamond

---
## 2b: Register Dewars
Dewars need to be registered in the database to be usable. DLS-owned Dewars will already have been registered and so will have an identifier of the form

`DLS-CY-00XX` 

If you are using your own Dewar, you will need to register it yourself

---
## 2c: Create Shipment
![](https://www.diamond.ac.uk/dam/jcr:16209158-a398-4f1b-947e-5787a456b771/Shipments.2021-10-19-10-54-09.png)

---
## Step 3: Add Samples to Shipment
You've created a Shipment. Now lets add some samples to it

---
## 3a: Create Container
![h:500](https://www.diamond.ac.uk/dam/jcr:2ca17415-6834-493f-9c8d-e24b097de302/ShipmentContents1.2021-10-19-10-54-09.png)

---
![h:500 ](https://www.diamond.ac.uk/dam/jcr:056818ed-9825-4a65-936d-7ae8b3539fe7/Container-samples.2021-10-19-10-54-09.png)
## 3b: Put samples in Container

---
![bg right](https://www.diamond.ac.uk/dam/jcr:c72b5a77-879a-41ca-98a1-79499ac9d97f/DewarLabel.2021-10-19-10-54-09.png)
1. Print the labels out
2. Stick them to your Dewar

---
# <!--fit--> 3. Ship it
![bg opacity](https://github.com/keeble/i19-1-workshop/raw/main/assets/ship-it.webp)

---
# Using ISPyB during your experiment
![bg opacity](https://yhatt-marp-cli-example.netlify.com/assets/gradient.jpg)

---
During the visit you can see what's going on
![w:900](https://github.com/keeble/i19-1-workshop/raw/main/assets/webcams.png)

---
## Data Collections Page, the distl plot
![w:1200](https://github.com/keeble/i19-1-workshop/raw/main/assets/dc.png)

---
## The concept of a data collection group
![w:1200](https://github.com/keeble/i19-1-workshop/raw/main/assets/dcg.png)

---
## the reciprocal lattice viewer
![w:1200](https://github.com/keeble/i19-1-workshop/raw/main/assets/rlv_button.png)

---
![bg](https://github.com/keeble/i19-1-workshop/raw/main/assets/rlv.png)

---
![bg](https://github.com/keeble/i19-1-workshop/raw/main/assets/rlv.png)
Press h for help

---
## Processing Summary
![w:1200](https://github.com/keeble/i19-1-workshop/raw/main/assets/processing.png)

--- 
## Dials / Processing output
![w:1200](https://github.com/keeble/i19-1-workshop/raw/main/assets/dials.png)

---
![bg opacity](https://yhatt-marp-cli-example.netlify.com/assets/gradient.jpg)
## Live Demo Time!

---
## Imminent Improvements
There are some improvements coming soon which should hopefully make ispyb _even more useful_ :+1:
- Use the supplied formula in shelxt solve
- Attach shelxt outputs correctly as processing outputs

---
# An introduction to ISPyB
![bg opacity](https://yhatt-marp-cli-example.netlify.com/assets/gradient.jpg)
Dean Keeble
I19 EH-1 Remote Users Workshop February 2023