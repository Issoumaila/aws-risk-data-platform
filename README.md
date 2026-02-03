# aws-risk-data-platform
AWS data lake for financial risk analytics (Bronze/Silver/Gold)
git clone https://github.com/Issoumaila/aws-risk-data-platform.git
cd aws-risk-data-platform
mkdir -p terraform diagrams
touch terraform/{main.tf,variables.tf,versions.tf,outputs.tf,README.md}
touch .gitignore
.terraform/
*.tfstate
*.tfstate.*
git add .
git commit -m "init: project structure for aws risk data platform"
git push
