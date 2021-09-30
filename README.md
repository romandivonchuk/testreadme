# To install Project on your local system, you need the following this steps:
1. Create folder project
 To avoid permissions issues **DO NOT place your projects folder on desktop** There should be **NO SPACES in the path**. e.g. `C:\Users\Your Name\projects`. It is better to put repositories into `D:\projects` or `C:\Users\YourName\projects`
 
2. Open folder project in IDE

3. Open the Terminal (gitBash) in your IDE
	<details>
	<summary>1How to Select default shell?</summary>
	<br>
	![Alt text](http://joxi.ru/GrqD0XPtRlyMPA)
	</details>

4. Install **yarn package manager** 
 ```
	npm install --global yarn
```
5.   **Clone** the repo 
 ```
	git clone --branch develop https://github.com/ita-social-projects/OoS-Frontend.git
```
6. Go to OoS-Frontend folder
 ```
	cd OoS-Frontend/ 
```
7. Run `yarn install`.
	 -  It may take some time
  
9. Run `yarn start` to check if it works.
	- At this point you should see the starting markup of the page at http://localhost:4200/ opened in your Google Chrome
