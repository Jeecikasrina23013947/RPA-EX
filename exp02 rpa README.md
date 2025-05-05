# RPA-Experiment--2
### NAME:JEECIKASRINA M
### REG NO:212223100015
### DATE:05.05.2025
## AIM:
  To display a Welcome Message based on the user's role or name using If and Switch conditions in UiPath.

## ALGORITHM:
1. Using If Condition:
* Start UiPath project.
* Use Input Dialog activity to get the user name or role.\
2. Use an If activity:
3. Condition: userInput = "Admin"
4. Then: Show Message Box: "Welcome Admin!"
5.Else: Show Message Box: "Welcome User!"

6. Using Switch Condition:
* Start UiPath project.
* Use Input Dialog to get role.
7. Use Switch activity:
* Set expression to userInput.ToLower (string type)
8. Add Cases:
"admin" → Message Box: "Welcome Admin!"

"manager" → Message Box: "Welcome Manager!"

"guest" → Message Box: "Welcome Guest!"

Default: Message Box: "Welcome Unknown User!"

## PROGRAM:
## If condition
![Screenshot 2025-04-17 142438](https://github.com/user-attachments/assets/c72cf614-0283-4c75-9126-d192a4b2603f)
![Screenshot 2025-04-17 142451](https://github.com/user-attachments/assets/2906fbf2-8625-4ada-a648-df3ff318c1d3)
## Switch condition
![Screenshot 2025-05-05 082414](https://github.com/user-attachments/assets/032747f8-4337-42c4-ac90-d1b8173a8264)
![Screenshot 2025-05-05 082426](https://github.com/user-attachments/assets/719c0494-0324-483c-a49f-3fa50bfe0c2b)
![Screenshot 2025-05-05 082432](https://github.com/user-attachments/assets/dd9d5a6a-ae1d-4a59-b2d5-2870949966f3)


## OUTPUT:
## If condition
![Screenshot 2025-04-17 142507](https://github.com/user-attachments/assets/c5248e8d-1a81-4d99-8841-848f99cf433d)
![Screenshot 2025-04-17 142514](https://github.com/user-attachments/assets/8a2add28-f908-4d4d-9666-7b1c00ff4854)

## Switch condition

![Screenshot 2025-05-05 082450](https://github.com/user-attachments/assets/44053fc2-f060-4a9b-be4a-f3ff5a830189)

![Screenshot 2025-05-05 082456](https://github.com/user-attachments/assets/5d06bead-3524-40b9-b63b-357c322fc3ae)

![Screenshot 2025-05-05 082514](https://github.com/user-attachments/assets/4aefc822-e48a-43a4-8319-b0521d1bde0c)

![Screenshot 2025-05-05 082520](https://github.com/user-attachments/assets/ce7cae86-5ed2-4e51-ae99-b7718f202fce)

## RESULT:
  Hence we display a Welcome Message based on the user's role or name using If and Switch conditions in UiPath.
