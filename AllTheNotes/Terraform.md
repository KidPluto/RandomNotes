# Terraform

[Automate your AWS cloud infrastructure](https://www.youtube.com/watch?v=SLB_c_ayRMo) by [freeCampCode.org](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)
* Installing Terraform was painful.  Had to manually move it to where you wanted it to live, and add the path to $path.
* Using Visual Studio Code editor, with the Terraform plugin, and this gives you command completion which works nicely.
```
terraform -v
terraform initializaiton
terraform plan
terraform apply
```
* He keeps using the term `declarative` to explain how the *.tf file doesn't behave like a plain script.  The fact that it evaluates what you are asking for verses what is already deployed.  I am not sure if that is the right word.