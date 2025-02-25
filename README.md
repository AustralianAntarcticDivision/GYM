# Generalised Yield Model (GYM)

The Generalised Yield Model is a fully flexible fish population projection model for examining the effects of different harvest strategies on stocks while taking account of uncertainties in input parameters (Constable & de la Mare, 1996). It was designed to provide a generalised version of the methods for estimating fishery yield based on the precautionary approach developed in the Commission for the Conservation of Antarctic Marine Living Resources. That precautionary approach was based on the work of Beddington & Cooke (1983) and developed to assess the precautionary yield of Antarctic krill. The assessment of krill yield was undertaken using the “Krill Yield Model” (Butterworth et al.,1992, 1994).

The Generalised Yield Model was first developed in 1995 for use in WG-FSA to provide an assessment tool based on the KYM but allowing for its general application to other stocks, such as Patagonian toothfish, and to provide for other forms for assessing the impacts of different catch scenarios, including trajectories based on a series of catches (mass) or fishing mortalities.

The primary part of the model is a flexible method for assessing the influence of different patterns of growth, natural mortality, spawning and fishing on estimates of yield and yield per recruit. It can also be used to evaluate stochastic stock trajectories under a specified catch regime. The model uses an adaptive Runge-Kutta algorithm to calculate stock trajectories and catch rates over a specified simulation period. The procedure numerically integrates a set of differential equations which incorporate functions that specify growth, mortality, age dependent selectivity and seasonal patterns in fishing mortality.

The outputs of the population model can then be used to determine catch limits according to CCAMLR decision rules (Constable et al. 2000) or for exploring the consequences of different types of harvest setting rules.

# The Grym

The Generalised Yield Model has been superseded by the Grym (Maschette et al., 2023). The Grym is an open source implementation of the Generalised Yield Model written in R. The Grym also provides more accurate results through changes to the governing equations originally proposed by Constable & de la Mare (1996). If you wish to use the Grym use this [code](https://github.com/AustralianAntarcticDivision/Grym). If you wish to rerun old assessments with the Generalised Yield Model software you can download it from this repository.


## Installation

To ensure that your GYM application and files are installed correctly, up to date and function correctly, when using this website for the first time please follow these steps:

Install GYM using setup
Replace existing files with latest components
Configure operating system
For guidance when installing, please refer to the readme file: Installation read-me [PDF]

### 1. Install GYM 5.01

Full setup GYM 501f download (posted 15 May 2018, previous versions 11 and 13 Oct 2004)
Release Notes readme (created 7 Nov 2003, posted 8 Nov 2003).
Once you have installed the GYM, you can add the latest versions of key GYM components by replacing the older ones in your directory.

### 2. Download Latest GYM Components

Please download these if you have not already done so and replace your existing files (some downloads may need to be unzipped). Please check the file creation and web posting dates to ensure you are using the most up to date version.

Latest GY interface download (created 13 Oct 2004, posted 13 Oct 2004, previous version 11 Oct 2004)
Latest GYM simulator: n/a
Latest GYI database: 2 databases — empty manual examples GYI501 databases (created 8 Aug 2003, posted 8 Aug 2003)
Latest GYM Kernel download (created 27 Sep 2004, posted 27 Sep 2004)

### 3. Configure Operating System

To run the GYM applications and files correctly you may also have to install the following database components: Microsoft MDAC (Data Access Components) 2.6 or later and Microsoft JET 4.0 or later (installed with Access 2000).

GYM post-install automated configuration download (created 9 October 2002, posted 23 September 2003)
The automated configuration will install automatically the required components based on the characteristics it identifies are needed for your operating system.

Additional downloads
Download a zip file containing the following:

Microsoft MDAC (Data Access Components) 2.6 or later (created 30 September 2002, posted 23 September 2003)
Refresh JET 4.0 SP3 for Windows ME, 2000 and later (created 27 September 2002, posted 23 September 2003)
JET 4.0 SP6 for Windows ME, 2000 and later (created 27 September 2002, posted 23 September 2003)
JET 4.0 SP6 for Windows 95, 98, and NT 4 (created 27 September 2002, posted 23 September 2003)
If you are experiencing any database problems after installing the above database components, it is suggested that you copy the command below and paste it in the "Run" window accessible via the "Start Menu".

regsvr32 "C:\Program Files\Common Files\Microsoft Shared\DAO\DAO360.DLL"

### 4. GYM User's Manual and Specifications

To assist all GYM users in getting the most out of the software, we have developed an excellent manual and additional example files. We strongly suggest that you take the opportunity to read the " ins and outs" of the GYM.

GYM 501b User's Manual and Specifications (posted 8 August 2003)

Part 1–3 GYM 501b User's manual download [PDF]
Part 4–5 GYM 501b Specifications download [PDF]
