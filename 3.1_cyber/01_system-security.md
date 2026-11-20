# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/450a0c91-fd9b-4787-b179-fb6a08a06dca" />


### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/5043d4a9-c669-444e-a9e8-93bfb8ca5856" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/47f6d7fb-6975-4e7b-bec4-7bf46d052faf" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/8f41e094-2c14-4840-bb09-6c7949571017" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/60874a9c-1ff0-4f68-b8d9-ebedba18e7ff" />




### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/ee96a03f-66c6-4230-badc-60ba1a7270c2" />


### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
