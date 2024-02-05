
# Predicting the amount of extracted gold

This project represents the final stage of the 10th sprint at the TripleTen Data Science Bootcamp. The goal is to build a machine learning model capable of predicting the quantity of gold extraction. This prediction will rely on data from three datasets containing information about gold extraction and purification, encompassing various parameters provided within the datasets.

## Description

### Features

In the three datasets, information is provided for four stages of the gold extraction process:

**Rougher Stage:**

* `Inputs:` Elements used in the process.
* `Outputs:` Concentration and tail values for specific elements, along with recovery—a crucial characteristic.
    * Additional details include calculations and various states.

**Primary Cleaner Stage:**

* `Inputs:` Elements related to the input information.
* `Outputs:` Concentration and tails for specific elements, along with state information.

**Secondary Cleaner Stage:**

* `Inputs:` Columns primarily consist of states.
* `Outputs:` Tails for the considered elements.

**Final Stage:**

`Outputs:` Concentration and tails for elements from previous stages, along with recovery information specific to this stage.

### Target

* Recovery after the rougher process and at the final stage of the procedure: `final.output.recovery`, `rougher.output.recovery`.