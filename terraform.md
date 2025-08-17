
### 1.What is Infrastructure as Code (IaC)

<p>Infrastructure as Code (IaC) tools allow you to manage infrastructure with configuration files rather than through a graphical user interface.</p>

<p>IaC allows you to build, change, and manage your infrastructure in a safe, consistent, and repeatable way by defining resource configurations that you can version, reuse, and share.</p>
<p>Terraform is HashiCorp's infrastructure as code tool</p>

* Terraform can manage infrastructure on multiple cloud platforms.
* The human-readable configuration language helps you write infrastructure code quickly.
* Terraform's state allows you to track resource changes throughout your deployments.
* You can commit your configurations to version control to safely collaborate on infrastructure.

To deploy infrastructure with Terraform below are baics 

* Scope - Identify the infrastructure for your project.
* Author - Write the configuration for your infrastructure.
* Initialize - Install the plugins Terraform needs to manage the infrastructure.
* Plan - Preview the changes Terraform will make to match your configuration.
* Apply - Make the planned changes.
