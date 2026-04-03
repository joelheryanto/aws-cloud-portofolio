#Auto Scaling Group Setup
##Konfigurasi
- ASG Name: joel-asg
- Launch Template: joel-launch-template
Min capacity: 1
Desired capacity: 1
Max capacity: 3
Region: ap-southeast-1 (Singapore)

##Fungsi
Auto launch EC2 saat traffic tinggi
Auto terminate EC2 bila traffic turun
