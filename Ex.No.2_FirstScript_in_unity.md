# Ex.No: 2  Welcome Script in Unity
## DATE: 23-10-2026                                                                        
## REGISTER NUMBER : 212224240094

## AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 

## Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.

## Program 
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to Unity");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
## Output:
<img width="1673" height="940" alt="Unity 6 Editor with 3D Monika Project (1)" src="https://github.com/user-attachments/assets/8aaa8dd9-87a0-4482-8e3b-6df22d6da3ca" />

<img width="1883" height="835" alt="Unity Editor Workspace with Monika Project Title" src="https://github.com/user-attachments/assets/f1797200-eb52-4af4-8be5-4966088a8fec" />


## Result:
Thus the welcome script was printed on Console Window  sucessfully.

