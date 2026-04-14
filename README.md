<p align="center">
<img src="https://cdn.worldvectorlogo.com/logos/active-directory-1.svg" alt="Active Directory logo"/>
</p>

<h1>Active Directory - Disabling User Accounts </h1>
This tutorial outlines the prerequisites and installation steps for disabling a user's account via Active Directory. By disabling a user's account, you prevent them from logging into a computer on your network. There can be several reasons to do this, but the most obvious is disabling a user's account after termination of employment.<br />


<h2>Video Demonstration</h2>

<p>N/A</p>

<h2>Environments and Technologies Used</h2>

- Active Directory
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Active Directory must be installed and configured correctly. 

<h2>Confirguration Steps</h2>

<p>
<img src="https://static.wixstatic.com/media/695ae6_210e0569c2164191a13a443562edc57d~mv2.png/v1/fill/w_600,h_336,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/695ae6_210e0569c2164191a13a443562edc57d~mv2.png" height="80%" width="80%" alt="Step1"/>
</p>
<p>
Open the Group Policy Management Console (GPMC). This can be done by searching gpmc.msc in the run window. 
</p>
<br />

<p>
<img src="https://static.wixstatic.com/media/695ae6_8ef0537529b64f438fbe28662079ee1a~mv2.png/v1/fill/w_600,h_336,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/695ae6_8ef0537529b64f438fbe28662079ee1a~mv2.png" height="80%" width="80%" alt="step2"/>
</p>
<p>
Edit Default Domain Policy.
</p>
<br />

<p>
<img src="https://static.wixstatic.com/media/695ae6_06a19cd3d398419eade6aa690eeffea0~mv2.png/v1/fill/w_600,h_351,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/695ae6_06a19cd3d398419eade6aa690eeffea0~mv2.png" height="80%" width="80%" alt="Step3"/>
</p>
<p>
Navigate to the Account Lockout Policy Settings.
</p>
<br />

<p>
<img src="https://static.wixstatic.com/media/695ae6_ded38a293c5c4585bcc5833bc3d9bdbc~mv2.png/v1/fill/w_600,h_336,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/695ae6_ded38a293c5c4585bcc5833bc3d9bdbc~mv2.png" height="80%" width="80%" alt="Step4"/>
</p>
<p>
Configure Account Lockout Policy Settings.
</p>
<br />
