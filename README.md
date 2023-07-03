# Attendance-Automation-System-using-AWS

✅This project aims to automate attendance management in educational institutions and organizations using AI and camera monitoring. The proposed system is expected to offer improved accuracy, efficiency, and real-time data. The system's benefits include improved engagement, regular attendance, and better learning outcomes for students.

<img src="https://github.com/charangavvala/charangavvala1706/blob/c2020922e5992b965fa994d8cd123db53afbec92/Architecture.jpg" alt="Architecture diagram">


We will be creating a website for attendance automation using services such as AWS cognito, lightsail, amazon rekognition, etc.

For authentication purpose, we will use AWS cognito so that students can log in on the website using their roll numbers.

Further, Amazon virtual cloud server (LightSail) will be used which provides a free static IP address to host the website. Select an OS from the list of options and build the website using the MEAN stack.Following successful login, the user will have the option to open the device camera and scan their identity card on the dashboard.

The Amazon Rekognition service which can store information about detected faces in server-side containers known as collections will be used to read and scan the image of students on the identity card. With this service, images are analyzed using a deep learning algorithm and are highly scalable. But first we have to manually add faces of students in that collection in one of the AWS regions in our account.

As soon as the card is scanned, the details of students are saved in DynamoDB.
