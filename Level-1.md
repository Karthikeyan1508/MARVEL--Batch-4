# Task 1 - Javascript

JavaScript, a dynamic scripting language, is widely used for web development to add interactivity and functionality to websites. With its versatility, JavaScript allows for client-side and server-side scripting, enabling dynamic content generation and user interface enhancements. JavaScript's ecosystem boasts extensive libraries and frameworks such as React and Node.js, fostering rapid development and scalability. Its ubiquitous presence across browsers and platforms makes JavaScript a cornerstone of modern web development, empowering developers to create immersive and responsive web experiences.

![image](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/ab492bec-a947-4720-ab02-4b6f708a5d9f)
![image](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/76999ff0-840d-4762-8315-c9ed9f8be907)

***

# Task 2 - Asynchronous

- Asynchronous JavaScript allows non-blocking code execution, crucial for managing tasks like data fetching and API calls without halting program flow.
- The program implements a callback-based approach to simulate cooking instructions for a food recipe, with each step represented by a function.
- Each step function invokes the next step via a callback upon completion, ensuring sequential execution and reflecting real-world cooking scenarios.
- Utilizing callbacks maintains a structured flow, enabling the recipe to progress asynchronously while allowing other operations to proceed concurrently, enhancing performance and user experience.
- Asynchronous programming with callbacks is essential in JavaScript development for creating responsive and efficient applications, vital for tasks such as user interactions and server communication.

![image](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/141eddf0-a78c-44e5-8fd8-96a38d4f5cdc)

***

# Task 3 - Promises

- **Clearer Code Structure:** Promises provide a cleaner and more readable code structure compared to callback-based approaches, making it easier to understand the flow of asynchronous operations.

- **Error Handling:** Promises offer built-in error handling through the use of `.catch()`, allowing developers to handle errors more effectively and ensure smooth execution of the program.

- **Chaining and Sequencing:** Promises enable chaining of asynchronous operations using `.then()`, simplifying the sequential execution of tasks and reducing callback nesting.

- **Asynchronous Parallelism:** Promises allow for parallel execution of asynchronous tasks using `Promise.all()` or `Promise.race()`, enhancing performance by running multiple tasks concurrently when applicable.
  
![Snap (1)](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/8b0e59cd-7890-489d-8e37-9906dfb36fc9)

***

# Task 4 - Get familiar with the command line and do the following subtasks

* Created a folder named "test" and navigated into it.
* Generated a blank file named "blank_file.txt".
* Listed files in the folder and created 2600 subfolders.
* Concatenated the contents of two text files using ```cat```.
* Completed the task successfully within the command line interface.
  
![Screenshot_2024-01-26_23_12_05](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/de3d2bdb-d90a-4387-9766-5a899355b575)
![Screenshot_2024-01-26_23_09_25](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/fc605c5e-5b52-4056-a188-9284a5f49c3b)

***

# Task 5 - VI

**VI: Navigating the Depths of Text Editing**

> - In the vast ocean of text editors, VI stands as a beacon of *efficiency* and *reliability*, tracing its roots back to the dawn of Unix systems.
> - Its minimalist interface belies a powerhouse of functionality, offering a plethora of commands and shortcuts designed to streamline text editing tasks.
> - VI's modal editing paradigm, where users seamlessly transition between *insert* and *command* modes, epitomizes its user-centric design philosophy.
> - Customization is key in VI's realm, empowering users to mold the editor to their unique needs through *settings*, *macros*, and *plugins*.
> - Yet, mastering VI is an odyssey in itself, a journey of discovery that rewards persistence with unparalleled speed and precision in text manipulation.
> - In the ever-evolving landscape of text editors, VI remains a *steadfast companion*, a testament to the enduring legacy of **simplicity**, **efficiency**, and timeless **elegance**.

### Features:

This is a sample Markdown file created using VI. Below are some key features illustrated:

1. **Opening a File:**
* ```vi <file-name>.<extension>```
* Example : `vi trial.txt`.

2. **Switching Modes:**
* Press `i` to enter insert mode (where you can type text).
* Press `Esc` to return to normal mode (for navigation and commands).

3. **Saving and Exiting:**
* To save changes and exit, press `Esc` to ensure you're in normal mode, the type `:wq` and press `Enter`.
* To exit without saving changes, press `Esc`, then type `:q!` and press `Enter`.

4. **Navigation:**
* Use arrow keys or `h`,`j`,`k`,`l` for left, down, up and right respectively.
* To move to the beginning of a line, press `0`.
* To move to the end of a line, press `$`.

5. **Editing:**
* Press `x` to delete the character under the cursor.
* Press `dd` to delete the entire line.
* Press `yy` to copy the entire line.

6. **Undo / Redo:**
* To undo changes, press `u` in normal mode.
* To redo changes, press `Ctrl + r` in normal mode.

7. **Searching:**
* Press `/` followed by the text to search for it.
* Press `n` to find the next occurence, or `N` to find the previous occurence.

![unnamed (1)](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/1a02d787-857d-45d6-981d-a96b72514ee6)
![unnamed](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/1b34b31b-e9bd-4364-aaff-e777e401043a)

***

# Task 6 - Linux Continued

The Task was to extract login times within a date/time range from the login logs & pipe this information into a text file and put it into a folder named logs.

1. **Understanding Regex and Piping in Linux:**
   - Regex (regular expressions) is a powerful tool for pattern matching in strings.
   - Piping (`|`) allows output from one command to be used as input for another in Linux.

2. **Understanding `grep` Command:**
   - `grep` is a command-line utility for searching text using regex patterns.
   - It extracts lines from files or standard input that match a specified pattern.

3. **Using `grep` to Extract Login Times:**
   - We can use `grep` with regex patterns to extract login times from the `last` command output.
   - For example, `last | grep 'username'` extracts login information for a specific user.

4. **Piping Output to a Text File:**
   - We can pipe the output of `grep` into a text file using the `>` operator.
   - This allows us to store the extracted login times for further processing.

5. **Creating Logs Folder and Archiving:**
   - We create a folder named "logs" to store the extracted login times text file.
   - Then, we use `gzip` and `tar` commands to compress the folder into a single archive file for easier storage and transportation.

6. **Benefits of Using `grep` and Piping:**
   - `grep` combined with regex offers a flexible and efficient way to filter and extract specific information from large datasets.
   - Piping allows seamless integration of multiple commands, enabling complex data processing workflows in Linux.

![unnamed (2)](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/498cb0ab-b58f-4679-a065-d7862f98062d)

***

# Task 7 - Introduction to Cloud Computing

![file_2024-03-25_06 11 39](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/1656d968-6a00-4035-bcbc-2eafa6a442e4)
![pic2](https://github.com/Karthikeyan1508/MARVEL--Batch-4/assets/121244307/a824ebf8-21c4-45a0-bda6-9c55960a1336)

