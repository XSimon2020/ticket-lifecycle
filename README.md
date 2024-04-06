# ticket-lifecycle

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle Examples</h1>
This demonstration outlines a simulation for ticket lifecycles in osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machine (VM)
- Microsoft Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- macOS

- Windows 10 Pro </b> (21H2)

<h2>List of Prerequisites</h2>

- Completion of [osTicket: Prerequisites and Installation](https://github.com/XSimon2020/osticket-prereqs)

- Completion of [osTicket: Post-Installation Configuration](https://github.com/XSimon2020/post-install-config)

<h2>Steps</h2>

<p>
1) <b>Create tickets.</b><br/>
Copy the link URL: http://localhost/osTicket/ and paste it onto Microsoft Edge within the vm to create tickets as end users. Type out the information and create the tickets as shown in the screenshots. 
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/7f42add8-2e43-4495-8834-6b3dc9517562">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/a14c04d9-b1a2-4588-84ca-7fe8f1b34c79">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/49b7eb91-a283-4c86-88b0-bba5851d2a72">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/b535f324-466c-4df1-8f06-9b8ab5c13aa7">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/1465189a-0740-4611-98c4-5a3a8a646af1">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/e06be716-c00e-4377-a713-b85f47965776">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/dc996099-bc01-4889-b81a-81892f263273">
</p>
<br/>

<p>
2)<b>Respond to tickets. (Part 1)</b><br/>
Copy the link URL: http://localhost/osTicket/scp/login.php and paste it onto Microsoft Edge within the vm to start responding to tickets as agents. Login as the agent assigned as a support lead previously. Stay on the "Agent Panel" to start assessing each ticket that is open. It is reasonable to first look into the help topic that is business critical, so select the ticket with "Business Critical Outage" as the help topic.

Since the topic is business critical that possibly requires an escalation, it may not be advisable to assign the ticket to a less experienced agent, so assign this ticket to yourself as the support lead agent. Configure the information such as "SLA Plan" as shown in the screenshots.

Respond to the end user's message about the issue as shown in the screenshots, basing around a possible scenario that could occur in a real world setting. Be sure the ticket staus is changed to "Resolved" and post your response.
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/16602f57-eb5f-4e69-b4ae-8392efe18f28">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/68328a04-9e7c-4b38-95f5-ea36b814cd4a">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/737b232f-f8ee-41fa-996a-4a3a35f6c546">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/13fbd182-e2e2-4676-9089-c601e3bcda7b">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/552ec0d7-959d-4753-968c-6a725d853e97">
</p>
<br/>

<p>
3)<b>Respond to tickets. (Part 2)</b><br/>
Still logged in as the current agent, look into the next open ticket based on priority. As a support lead, you can assign this ticket to a subordinant agent since the issue can be handled by them, so assign it to the other agent created while configuring the settings just like the screenshot. 

Since the ticket is assigned to someone else, the last open ticket should only be considered for this agent. Configure the settings and respond to the end user as shown in the screenshots. Be sure to change the status to "Resolved" before posting a response.
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/19274416-496d-414c-80cc-1caa824f5940">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/c4c6632e-06a7-4ae1-a18f-2c8edd2eaa06">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/296ff188-1a9d-4d0d-b8a4-8fc62c981a5d">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/aea3df1e-2a5f-44ac-b813-2ef1c837b5d9">
</p>
<p>
<br/>

<p>
4)<b>Respond to tickets. (Part 3)</b><br/>
Log out of the current agent account and log in to the other agent assigned to the ticket that is left open to start responding to it and ensure that it is still open. Since the settings have already been configured from the previous agent, respond to the end user right away as shown in the screenshot based on how a real scenario would play out. Be sure to change the ticket status before posting the final response.
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/94b67b13-92fb-4c0d-96b5-611b689449ec">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/b96457e1-65a6-4d50-94cd-759606f67730">
<img width="1168" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/df680fe0-2571-4b42-a9cc-7218dd0f4d1b">
<img width="1202" alt="image" src="https://github.com/XSimon2020/ticket-lifecycle/assets/111246513/03f2ff1d-97a9-4a97-ac3e-7fb124146019">
</p>
<br/>

<b>This marks the end of the demonstration.<b>


