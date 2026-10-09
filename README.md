ESLINT
=> It is a static analysis tool used to ensure code quality. 
=> It is an open source linter specifically designed for Java script, examining code 9for stylic erors and potential problems based on customisable rules.




Standard JavaScript Style with ESLint vs. Manual ESLint Configuration
a) .......... Standard JavaScript.........
Many teams prefer a standard style guide configured with ESLint, which enforces consistent code quality across projects.

Pros:

1) Consistent Style: Everyone follows the same style, making code easier to read and maintain for the whole team.
2) Reduced Friction: A standard guide minimizes debates on stylistic choices, allowing developers to focus on functionality.
3) Error Reduction: Standard style guides often include rules that detect common syntax errors and prevent coding mistakes.
4) Automatic Formatting: With the --fix flag, ESLint can correct many style violations automatically, saving time on manual reformatting.
5) Up-to-Date Best Practices: Standard guides are often updated with industry best practices, keeping your code aligned with current standards.
6) Best for: Teams or projects where uniformity and collaboration are priorities, or when you want a proven, minimal-setup solution to maintain code quality.


b) .........Manual Configuration.........
For projects with unique requirements, manually configuring ESLint rules allows teams to create a tailored set of guidelines.

Pros:

1) Customization: You can define rules based on specific project needs, allowing greater flexibility in code style and error detection.
2) Fine-Tuned Control: Adjust linting to align precisely with your team’s development style and preferences.
3) Adaptability: For projects that don’t fit a standard guide, manual configuration allows for unique and evolving coding practices.
4) Best for: Projects with highly specific requirements, smaller teams with distinct coding practices, or when flexibility is prioritized over strict adherence to a standard style.





ESLint Configuration
1. create a new directory 

2. initialize the project with Node.js
   - npm init -y 
-this creayes a package.json file

3. Install ESLint as a Development Dependancy
    - npm install eslint --save-dev

4. Setting up ESLint
     -npx eslint --init

- Follow the Setup Prompts below, selecting the indicated response for each:
. How would you like to use ESLint?
    -Select To check syntax and find problems
. What type of modules does your project use?
    -Select JavaScript modules (import/export)
. Which framework does your project use?
     -Select None of these
. Does your project use TypeScript?
    - Select No
. Where does your code run?
   -Select Node , if Browser select browser
. The config that you've selected requires the following dependencies: eslint@9.x, globals, @eslint/js ? Would you like to install them now?
    - Select Yes
. Which package manager do you want to use?
    - Select npm
. This process creates a eslint.config.mjs file which contains your ESLint configurations. 



5. Create a java script file, write code , leave out an undefined variable.

6. Running ESLint in terminal
     - npx eslint example.js

7. Fix errors and run ESLint again, there should not be output if code has no errors or warnings.

8. ESLint can be customized. - in the eslint.config.mjs file, you can add or adjust rules as needed.
    