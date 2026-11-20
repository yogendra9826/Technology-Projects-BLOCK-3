# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/39b21d8c-ad84-409e-931f-25d60bbc81a4" />


### Questions

1.  Who owns the file?
2.  What are the default permissions?

### Reflection

Why is file ownership important in Linux systems?

------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/c7932a8e-798b-4f32-ab76-2fe84fd00694" />


### Questions

1.  Who can read the file now?
2.  Who cannot access it?


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/0ba3d1f1-a00f-49ea-a5fa-bcad4919bc13" />


### Questions

1.  Who can access the file now?
2.  Why might this configuration be dangerous?

