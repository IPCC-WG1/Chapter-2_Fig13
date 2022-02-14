##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is MATLAB code to produce IPCC AR6 WGI Figure 2.13, panels a and c
# Creator: Juan A. Rivera, IANIGLA/CONICET 
# Contact: jrivera@mendoza-conicet.gob.ar
# Last updated on: July 8th, 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: This code calculates the trends in surface specific humidity and surface relative humidity using OLS regression with significance assessed following AR(1) adjustment after Santer et al. (2008)
# - Input data: NetCDF files of gridded global surface specific and relative humidity from HadISDH dataset. The files can be accessed at: https://catalogue.ceda.ac.uk/uuid/02fd1d886bad40f3bb2eef3271900823
# - Output variables: The code plots each figure panel as in the report
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: MATLAB R2017b
# - Landing page to access the software: https://www.mathworks.com/products/matlab.html?s_tid=hp_products_matlab 
# - Operating System: Microsoft Windows 10 Home Single Language, last update June 13th, 2021
# - Environment required to compile and run: Not applicable
#  ----------------------------------------------------------------------------------------------------
#
#  License: Creative Commons Attribution 4.0 International License (http://creativecommons.org/licenses/by/4.0/)
#
# ----------------------------------------------------------------------------------------------------
# How to cite:
# When citing this code, please include both the code citation and the following citation for the related report component:
########################################################################














Am keeping this for reference:
# ----------------------------------------------------------------------------------------------
# Acknowledgement: The template for this file was created by Lina E. Sitz (https://orcid.org/0000-0002-6333-4986), Paula A. Martinez (https://orcid.org/0000-0002-8990-1985), and J. B. Robin Matthews (https://orcid.org//0000-0002-6016-7596)