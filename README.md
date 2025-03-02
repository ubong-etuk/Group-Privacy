# Group-Privacy Analysis
This research presents PriSAT as a tool for investigating group privacy. The PriSAT tool is designed for analyzing privacy satisfaction in software design. It is implemented in Java programming language and utilizes an epistemic modal logic approach for privacy analysis. The tool allows for various forms of privacy analyses, one of which is group privacy requirements satisfaction analysis. 

Given a group of interacting users and a specific privacy requirements for the group, the following steps are required in using the PriSAT tool to analyze the extent to which the  group satisfies the privacy requirements. 

**Step 1**: Start the tool. This displays the different interfaces that constitute the tool. 
![image](https://github.com/user-attachments/assets/d234a90e-af38-4598-8fea-3f64fc70e646)

**Step 2**:  Configure the group under consideration. This involves generating an interaction network of users and assigning disclosure protocols to each interact between the users in the network.
![image](https://github.com/user-attachments/assets/cf4303b4-7c30-4f75-8431-224aff10c634)

**Step 3**: Generate instances of the group privacy requirements. This step involves selecting the type of group privacy requirement to investigate (instance-based or role-base) and generating the possible instances of that requirement type. 
![image](https://github.com/user-attachments/assets/e6966597-6f78-486c-9991-fa725aed8723)
![image](https://github.com/user-attachments/assets/30cdeb4a-7b9f-49e0-a364-baff670aa9ac)

**Step 4**: Select the instance of the privacy requirements. This involves selecting the specific requirements instance(s) from the state space of instances generated in Step 3 for analysis. 
![image](https://github.com/user-attachments/assets/eaaf2975-3157-44a5-96b9-8b9876cf50b9)

**Step 5**: Verify the privacy requirements satisfaction . This step initiates the analysis that determines the extent the configured group in Step 1 satisfies the selected instance of privacy requirements in Step 4.
![image](https://github.com/user-attachments/assets/2a2d55e3-607f-43e6-b02b-2a862b16d856)

**Step 6**:  Display the requirements satisfaction outcome . This step displays the outcome of requirements satisfaction using the sat tree to highlight the sat outcome of each assertion in the selected requirements. 
![image](https://github.com/user-attachments/assets/09ab2610-1011-4686-b160-34ed4c42dc6f)

