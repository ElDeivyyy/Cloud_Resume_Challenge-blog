# Cloud_Resume_Challenge-blog

The Cloud Resume Challenge: Lessons Learned and Services Explored 

Introduction 

When Professor Lontok introduced the cloud resume challenge as a project I got pretty 
excited because I would get experience with cloud technologies and I could test myself. 
The challenge takes a hands-on approach to learning cloud development, and it certainly 
accomplished the goal. This post reflects on my experience working through each stage, 
the insights I gained, and the services I used, with the hope that my testimony helps 
somebody else.  

Frontend  

The project started with setting up a static website using HTML and CSS, hosted on AWS 
S3. Initially, this seemed straightforward but bringing it all together required attention to 
detail and patience. While HTML and CSS are considered entry-level, I gained a new  
appreciation for these foundational languages, especially in making my site functional and 
visually appealing. Hosting it on S3 added another layer of difficulty, turning my resume into 
a cloud-hosted portfolio. Seeing it live online was a great experience, I was so happy when I 
first saw it I couldn't believe it. I shared it with my parents and friends and even though the 
first sketch was a blend and boring page I was proud of it because I put effort into it and 
that’s what made it precious to me.  

Since I never had the fortune to work on a project like this before most if not everything, I 
was doing was new to me. A challenge I encountered while doing the front end was adding 
security with HTTPS and DNS. I had to use AWS certificate manager to provide HTTPS to 
obtain a valid SSL certificate and apply it to my S3 website. This was my first experience 
with these services, and I learned how much security impacts users' trust accessibility. 
After being done setting up HTTPS I was about to encounter my biggest challenge of them 
all which was adding a visitor counter. I’m not joking when I say that this took me ages to 
understand and fix when I encountered a problem. This step shows me the importance of 
patience and celebrating small victories is always important for your morale. While doing 
the counter there was a moment where I changed or deleted something by accident and 
got so stressed that decided to start over again. A valuable skill I learned from this was to 
trace back my steps to see what I did wrong and how can I prevent it from happening again. 

Backend  

I used python to write an API that allowed my visitor counter to communicate with a 
DynamoDB table, storing data for each visit that my website would receive. This step 
brought the front end and the back end together, illustrating how they interact. While the 
initial setup was challenging, working through it helped me understand the importance of 
reliable backend infrastructure. Seeing my visitor counter going up in real time was 
incredibly rewarding. Implementing CI/CD with GitHub Actions introduced me to 
continuous integration and deployment (CI/CD), automating code testing and deployment. 
Setting up workflows on GitHub Actions was a new experience, but it emphasized the 
importance of automation in modern development. Every code update triggered a series of 
tests, ensuring my work was consistently reliable and reducing the risk of human error. 
Automation not only saved time but also added a professional layer to the project, making 
it feel like a real-world deployment. To manage and deploy resources consistently, I used 
Terraform for Infrastructure as Code (IaC). This step simplified the setup of various AWS 
services, allowing me to create repeatable infrastructure configurations. Though learning 
Terraform syntax was initially challenging, this part of the project gave me a sense of the 
scalability and reliability that cloud infrastructures offer. IaC ensures consistency across 
environments, an invaluable skill for any future cloud work. 

Reflecting on the Experience: Challenges, Growth, and Future Goals 

Completing the Cloud Resume Challenge was more than a technical journey—it was a 
lesson in perseverance and problem-solving. Each step required learning new skills, from 
coding to infrastructure management. The most fulfilling part was troubleshooting issues 
and eventually seeing everything come together. Looking back, the journey taught me the 
value of patience and adaptability, and it reinforced my interest in pursuing cloud 
technology further. This challenge was both demanding and rewarding, giving me a solid 
foundation in cloud development. I came away with not only technical skills but also a 
renewed confidence in tackling complex projects. For anyone considering a similar journey, 
I wholeheartedly recommend it. The Cloud Resume Challenge showed me that each step, 
each error, and each solution contributed to building a stronger skill set that I can now 
carry forward into my career.
