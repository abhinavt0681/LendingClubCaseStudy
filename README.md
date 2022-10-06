***License**
This project is open source and available under the **BSD License**. Meaning you can copy and commercialise this. :-)*


# **Lending Club Applicant Loan Worthiness Analysis**
> A Data set of Loan Applicants in the organisation Lending Club has been presented. Our target is to make recommendations to the organisation, as to which **applicants are:**

>1. **Worth Discharging Loan.**
>2. **Not Worth Discharging Loan.**

Two Greatest Sources of Loss for Any Lending Organisations are Closely Related but Different Reasons:
1. **Rejecting Loan Of The Applicant That Could Have Paid.**
2. **Accepting Loan Of The Applicant That Fails To Pay.**

Both these reasons cause huge losses to the lending company. Therefore, the they need to be optimised as much as possible. 

## **Table of Contents**
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## **General Information and Background**
Humans are visual learners, our senses to decipher an image far supercedes our ability to decipher text. Even as we are reading very difficult book, essentially, as we read it, in our brains we create a visual image of what is described in the text. 

Therefore, as we read text, it can be said that we are essentially interpreting it into a form our brain understands, "visuals and audio".

Thats exactly what we are doing over here. A 34 megabyte large CSV txt datasheet has been given to us, our job is to turn it into picture for our client. 

We take hours and days to choose the right graphs and visual depictions, relevant so that nothing important gets excluded, nothing unwanted gets included. So our client is now able to look at these images (graphs basically) for a few minutes and hours and make a decision. 

We essentially are turning this massive 34 megabyte text information into a few understandable graphs, that are based on it and accurate. 

This is whole technique can be called "Data Analysis".

## **Business Problem**  
 We are applying this incredible text-to-graph technique using different Python Based Libraries to turn a dataset of a large number of people that have applied for a loan with our client "Lending Club".

 Now it is our job to **make sure they pick the right applicants to discharge loans to.**

### **This is how we achieve it.**
We are going to use number crunching libraries written in C for python, to crunch the numbers into operable dataTypes, and them feed them into libraries written to turning them into Graphs.

Once the numbers are turned into graphs, we will have a very good understanding of correlation of different factors with loan repayment rate.

Using this Information we will give the recommended actions on the applicants to our cient.

## Information about Dataset
Very generously a raw, well labeled datasheet of applicants, in a csv format has been given to us by our client. This made our task very easy. But still, a lot of operations need to be conducted on the datasheet before running an Analysis on it, otherwise our results maybe wildly skewed. This would destroy the business decisions, as they are to be based on the recommendation generated as a result of analysis done on the input data.

And this input data, is what we need to prepare the from the dataset called, **"loan.csv"** given to us by our client lending club, and an accompanying **"Data_Dictionary.xlsv"** to be used as a reference by us for understanding the meaning of different column names in loan.csv. 

>This process is called **Data cleaning.**

 A variety of automated and manual operations, and different softwares like spreadsheets, apart from just python based libraries, can be used to achieve this.

 Which is exactly what we have done.

The presentation of data should be filtered to a point where by even a child can understand it. At the same time, we shouldn't forget what einstein said, "Make everything as simple as possible, but not simpler"; therefore, in the name of presentability, **the datapoints and analysis can't be skewed to the point of tampering the key values.**


## **Conclusions**
Final File Structure,

**1. Group_Facilitator_AbhinavTyagi.ipynb**
> Containing Jupyter-Lab With Final Outputs

**2. Group_Facilitator_AbhinavTyagi.py**
> Final Jupyter-Lab Notebook Converted to machine executable Python Script.

**3. Group_Facilitator_AbhinavTyagi.pptx**
> Presentation in Microsoft PPTX format

**4. Group_Facilitator_AbhinavTyagi.pdf**
> Same Presentation in Adobe PDF format.
<br>
loan.csv is in dataset/ directory




## Technologies Used
### **Operating System(s)**
   * Windows 11 Build 22H2 Pro N, 2022, 22621.521m WFEP 100.22634.1000.0
   * Debian Based Linux Canonicle Ubuntu 22.04 LTS
   * UEFI Dual Boot Setup to switch between Microsoft NT AND UNiX Work Environmnets 
   * WSL Ubuntu On Windows Used Sparingly



### **Command Line Interactions**
   *  Windows Terminal 1.15.2713.0
   *  Windows PowerShell 7.2.6
   *  Debian Terminal on Ubuntu LTS.
    
### **IDEs**
   *  Jupyter-Lab
   *  Notepad
   *  Microsoft Visual Studio Code

### **Package Managers/Version Control Systems**
   *  git (version 2.37.3)
   *  pip (pip 22.1.2)
   *  Anaconda -- conda 22.9.0
   *  apt-get

### **Programming Languages Used**
  * Python (3.9.13); (Bundled With conda)
  *  C (Based Libraries Imported in the Code, Numpy, pandas, etc)

### **Libraries Used**
  *   Seaborn (0.11.2)
  *   re (regex interpreter)
  *   matplotlib (3.5.2)
  *   numpy (1.21.5)
  *  pandas(1.4.4)
  *  nbconvert (6.4.5)

### **SpreadSheets and Presentation Softwares**
  * Microsoft Excel 2016
  * Microsoft Powerpoint 2016
  * Sparingly used Google Sheets

### **Browsers/Browser Engines**
    Chromium Based 106.0.5249.91 Browser Brave 1.44.105
   
    Firefox Gecko 103.0.2 / 9 August 2022 Browser Engine.

### **Communication Technologies**
  * Airtel Fiber

  * Realtek 1000 Megabits/Sec Ethernet Adaptor

  * Broadcom WLAN Adaptor

  * **Google Mail, IMAP** for communication between team and client (UpGrad)
<br>

### **Development Machine Hardware**

* AMD RYZEN 1600x Hexacore Processor, x64_86 Architect, 6 core 12 threat, 95 Watts TDP. 
* Gigabyte B450-M-DS3H Motherboard.
* *MBR* (Master Boot Record Partitioning) *ext4*, for Linux, on spinning hard drive.
* **GPT NTFS filesystem** for Windows on Solid State Drive.
* Final Runs done on WD SATA-III Solid State For Efficiency.
* **16 GiB, tri-channel memory**, 2x4GiB and 1x8GiB Crucial DDR4 throttled to 2666MHz clock per slot.
* Gigabye AMD **Radeon RX 570**, 4GiB Memory GDDR5 7000MHz Clock, 2x 3700 RPM 90mm Blade FANS, PCI-e x16 3.0 32000MiB/s Bridge, **Polaris 20 XL** (215-0910052)**GPU 1244 MHz** Clock. 150W Peak Power.
* **Corsair SV450**, SV Series, 80 Plus Bronze Certified, **450 Watt PSU**.


    
### **Cloud Services Used**
Git/Github. (*All other operations and development done on local machine, no cloud services used.*)

### **Instruction Set** Linear Algebra Kernel Library

<br>**OpenBLAS 0.3.21**
   *(Basic Linear Algebra Subprograms) (Faster Operations on AMD hardware, the default Intel Math Kernel Library is throttled on non-Intel machines. If you aren't using AMD processor, MKL will be faster on your machine.)*

<br>
<br>
<hr>

## Acknowledgements

## Contact

Created by [@abhinavt0681] - feel free to contact me!

Wouldn't be possible without my very helpful and experienced partner in this Project, **Vinay Pai**. 


## Project Undertaken  as a part of Upgrad Case Study By
**Facilitator**<br> 
```python
Abhinav Tyagi 
abhinav@vayubiotech.com 
+91-9755504588          
```       

**Team Member:**                  
```python
 
Vinay Vijaykumar Pai 
vinaypai1977@gmail.com 
+91-8861039039 

```


**Thanks Upgrad and Lending Club to Give us the Opportunity To Perform this Analysis.**