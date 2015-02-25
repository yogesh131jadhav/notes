# Data transfer within github and your personal device

** As we seen in previous document Git hub Provides 3 ways to manage and transfer data **
* Create Own repository
* Clone repository
* Pull changes


#### Create Own repository

We can start github by create our own repository.
By following simple steps we can create our own repository over github easily.

**step1 ** 
- Create account on github.com by your email id.

**step2 ** 
- Verify your Github account by verifying Mail sent to you by Github.

**step3 ** 
- Now on Github we get an option "New Repository" choose it and create new repository.

**step4 ** 
- Repository is somewhere your main category or project. After Creating repository you will get "ssh key". It will required on "Step 7".

**step5 ** 
- Create folder on your system keeping name of that folder of repository.

**step6 ** 
- Write click and select option "git bash".

**step7 ** 
- Enter commands "git remote add origin ssh_key (Which you get on 4th step)".

**step8 ** 
- Then enter command "push -u origin master".

**step9 ** 
- Congratulation you have created your Git repository in your account successfully as well as you have created its local repository too.


#### Clone repository 

Git hub provided this option for the case where repository is already created. Using this functionality we can easily share our projects or documents with our team.

Important think which we need is **"ssh key"** of repository which we are going to clone.

**step1 ** 
- Get "ssh key" of repository which we want to clone.

**step2 ** 
- Add command "git clone ssh_key"

**step3 ** 
- Congratulation you have cloned your Git repository to your personal device.

#### Pull changes

Pull change is similar with Clone repository. The difference is we use Clone repository when we start working on it first time or newly. While in pull request we start our work by pulling work from server so that we will get all changes deployed by other user/developers.

**step1 ** 
- Checkout to the branch on which you want to work.

**step2 ** 
- git pull origin branch_name.

**step3 ** 
- Congratulation you have pulled updated code of that branch.