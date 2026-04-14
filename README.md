<p align="center">
<img src="https://cdn.worldvectorlogo.com/logos/active-directory-1.svg" alt="Active Directory logo"/>
</p>

<h1>AD-Group Policy Management - Lockout User Accounts </h1>
This tutorial outlines the prerequisites and installation steps for configuring Group Policy to lock out a user's account after a set number of attempts. In this tutorial, we will be setting that number to 5 attempts .<br />


<h2>Video Demonstration</h2>

<p>N/A</p>

<h2>Environments and Technologies Used</h2>

- Active Directory (Testing Results)
- Group Policy Management
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Active Directory must be installed and configured correctly. 

<h2>Confirguration Steps</h2>

<p>
<img src="https://static.wixstatic.com/media/695ae6_e2769fe5184f40899325befe6dc2e52a~mv2.png/v1/fill/w_600,h_337,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/AD-1.png" height="80%" width="80%" alt="Step1"/>
</p>
<p>
Open the Group Policy Management Console (GPMC). This can be done by searching gpmc.msc in the run window. 
</p>
<br />

<p>
<img src="https://static.wixstatic.com/media/695ae6_ff8192023b6a469598561363db1c16b7~mv2.png/v1/fill/w_600,h_337,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/AD-2.png" height="80%" width="80%" alt="step2"/>
</p>
<p>
Edit Default Domain Policy.
</p>
<br />

<p>
<img src="https://static.wixstatic.com/media/695ae6_bb1833a631934583997178354dea0e58~mv2.png/v1/fill/w_600,h_337,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/AD-3.png" height="80%" width="80%" alt="Step3"/>
</p>
<p>
Navigate to the Account Lockout Policy Settings.
</p>
<br />

<p>
<img src="https://static.wixstatic.com/media/695ae6_9423019c0725472cab660ce21b17e291~mv2.png/v1/fill/w_600,h_337,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/AD-4.png" height="80%" width="80%" alt="Step4"/>
</p>
<p>
Configure Account Lockout Policy Settings.
</p>
<br />
