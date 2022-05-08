# Conditional-Access

- <em> Requires Azure AD P1 License </em>


What is Conditional-Access?

- They're a more flexible MFA policy. Think of them as if-then statements; If a user wants to access a resource, then they must complete an action. 
- They're another life of defense and is only enabled after the single factor authentication. Similar to MFA but offers more flexibility.

Why do we need Conditional Access?
- Imagine if you were an IT admin and had enable MFA on 10,000 employees. 
- - IT admin can use conditional access and apply them to users and groups that contain thousands of employees
- More flexibiity!
- Require users log in via a certain OS.
- Require users log in from a certain location
- Require device to be marked as compliant
- Require device log in from an approved client app
- and more conditions ...

Include and Exclude:
- Conditional Access offers features to include certain users or exclude specific groups.
- Also can enable the Conditional Policies to certain applications such as Sharepoint or Azure Portal.

How to create Conditional Access Policies?
<strong> <em> Before creating conditional access policies, IT admin may need to disable <em> security defaults </em> </em> </strong>

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167276648-0286c282-a8d6-496b-8836-48302512ec8c.png" height="80%" width="80%" alt="Conditional Access"/>
  
<p/>


- Navigate to Security > Conditional Access > Create a new policy

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167276683-7183a991-a4bb-4baf-b53b-c7f420302921.png" height="80%" width="80%" alt="Conditional Access"/>
  
<p/>

Common decisions:

- Block access
- Grant access and require:
- - multi-factor authentication
- - device to be marked as compliant
- - Hybrid Azure AD joined device
- - approved client app
- - app protection policy (preview)


In the screenshot below, IT admin can set conditional access policies to include or exclude particular users or groups

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167276347-e3a6f9f9-00c2-42ae-9ffc-aa0efcc9a126.png" height="80%" width="80%" alt="Conditional Access"/>
  
<p/>

Below, conditional access can require users log in from a particular location via a trusted IP.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167276394-3b5509d4-6c5c-49c2-82d5-f6247e180963.png" height="80%" width="80%" alt="Conditional Access"/>
  
<p/>

Report Only feauture (Testing purposes)
