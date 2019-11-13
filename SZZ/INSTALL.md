# HOW TO RUN

### Requirements
1. `python 3`
2. `jupyter notebook`

### Procedure:
1. Clone this repository into your userhome folder in the system :
   ```
   git clone https://github.com/yusufsn/DifferentDiffAlgorithms.git
   ```
   output: `/Users/<yourusername>/DifferentDiffAlgorithms/`
2. Change the directory into `SZZ`, and create a new directory `datasource`. 
   
   ```
   cd DifferentDiffAlgorithms/SZZ/
   
   mkdir datasource
   ```
3. Change the directory into `datasource`, then clone a target repository from GitHub, e.g. `Apache ActiveMQ`.
   
   ```
   git clone https://github.com/apache/activemq.git datasource/activemq
   ```
   
4. Run `jupyter notebook`.
5. In the `jupyter notebook`, open all source code files in the directory `code_document`.
6. Only for source code file no. 00, put the exact name of the cloned repository in the variable named `project` and the project key / bug identifier in the variable `bugidentifier`. Different projects have different bug identifiers.
   e.g. For `Apache ActiveMQ` project -> `project = "activemq"`, `bugidentifier = "AMQ"`
7. Run all cells in all source code files from number `00` to number `10` sequentially.
8. The summary results of the SZZ implementation for each project are saved in CSV format in the directory of `~/DifferentDiffAlgorithms/SZZ/project_analyses/<yourtargetedprojectname>/05_validation/05_stats/`.
9. Repeat step 3 to 8 for different projects.
