### 1. **Open the Terminal**
   - **On a MacBook:** Use Spotlight search (Cmd + Space) and type "Terminal" to open it quickly.

### 2. **Navigate to Your Working Directory**
   - Once the terminal is open, navigate to the directory where your `hello-world` project is located. Use the `cd` command like this:
     ```bash
     cd /Users/satoshinakamoto/Exercism/bash/hello-world
     ```

   - If you've created a shortcut (`alias`) to navigate to this folder faster, you can use that instead.

### 3. **Check the Files in the Directory**
   - To verify that you're in the correct folder and see the files available, run:
     ```bash
     ls -l
     ```
   - This will display the files in your directory, ensuring that `hello_world.sh` is present and ready to be edited or executed.

### 4. **Edit `hello_world.sh` File**
   - Open the `hello_world.sh` file in a text editor to make changes. You can use the terminal text editor `nano`:
     ```bash
     nano hello_world.sh
     ```
     Alternatively, you can use Visual Studio Code (VS Code) or another editor:
     ```bash
     code hello_world.sh
     ```

   - Make your changes and save the file. If using `nano`, you can save by pressing `CTRL + X`, then `Y`, and `Enter`.

### 5. **Make the File Executable**
   - If you're running the file for the first time or if permissions have changed, make sure the `hello_world.sh` file is executable:
     ```bash
     chmod +x hello_world.sh
     ```

### 6. **Run the `hello_world.sh` File**
   - Execute the file to see the output:
     ```bash
     ./hello_world.sh
     ```
   - This command will run all the commands in your `hello_world.sh` script and display the output in the terminal.

### 7. **Modify and Re-run the Script if Needed**
   - If you need to make changes to your code, go back to step 4 to edit `hello_world.sh`.
   - Save the changes and rerun the script using:
     ```bash
     ./hello_world.sh
     ```

### 8. **Submit Your Solution to Exercism**
   - Once you're happy with your solution and want to submit it to Exercism, use the following command:
     ```bash
     exercism submit hello_world.sh
     ```