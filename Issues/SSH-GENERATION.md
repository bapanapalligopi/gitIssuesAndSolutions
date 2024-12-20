Here is a list of all the commands you used in your terminal session. You can copy this into a document for future reference:

---

### List of Commands Executed:

1. **Navigating directories:**
   ```bash
   cd users
   cd C:
   cd users
   cd admin
   cd .ssh
   ```

2. **Generating an SSH Key:**
   ```bash
   ssh-keygen -t rsa -b 4096 -C "bapanapalligopi7@gmail.com"
   ```

3. **Displaying public key:**
   ```bash
   cat ~/.ssh/id_rsa.pub
   cat ~/.ssh/bitbucketgopi7.pub
   ```

4. **Navigating back to your project directory:**
   ```bash
   cd B:
   cd Internship/
   cd internshiproject/
   cd merchantfeedbackmanagementsystembackend/
   ```

5. **Reinitializing the Git repository:**
   ```bash
   git init
   ```

6. **Adding files to staging:**
   ```bash
   git add .
   ```

7. **Checking the status of the Git repository:**
   ```bash
   git status
   ```

8. **Adding the remote repository:**
   ```bash
   git remote add origin git@bitbucket.org:gopigopi1217/mfmsbackend.git
   ```

9. **Setting the remote URL (if the remote origin already exists):**
   ```bash
   git remote set-url origin git@bitbucket.org:gopigopi1217/mfmsbackend.git
   ```

10. **Testing SSH connection to Bitbucket:**
    ```bash
    ssh -T git@bitbucket.org
    ```

11. **Starting the SSH agent:**
    ```bash
    eval "$(ssh-agent -s)"
    ```

12. **Adding the SSH key to the agent:**
    ```bash
    ssh-add ~/.ssh/bitbucketgopi7
    ```

13. **Pushing changes to the remote repository:**
    ```bash
    git push -u origin main
    ```

14. **Checking the current remotes:**
    ```bash
    git remote -v
    ```

---

### Notes on Key Steps:

- **SSH Key Generation**: You generated a new SSH key using `ssh-keygen` and saved it as `bitbucketgopi7`.
  
- **Adding SSH Key to Bitbucket**: Make sure to add the generated SSH key to your Bitbucket account (found in `~/.ssh/bitbucketgopi7.pub`).
  
- **Git Push**: After configuring the SSH key and setting the correct remote URL, you successfully pushed your code to Bitbucket.

---

Let me know if you need any further details or additional help with the commands!
