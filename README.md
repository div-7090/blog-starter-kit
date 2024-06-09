# Take home assessment
1) From this list, rank your 5 most favourite and 5 least favourite support tasks. Provide a brief explanation for each.

> Most Favourite Support Tasks:

•	Respond to 25+ support requests via email every day.
This is one of the most favourite tasks as I did just this in my previous role. I’m trained and have the expertise in supporting a global customer base over live Chats/Calls/Emails on a day-to-day basis and I enjoyed doing it. 

•	Write and maintain support articles and docs pages.
I always believe that writing and maintaining support articles help in handling similar support requests at a later point. It would also come in handy and can be shared with the ones in need such that the overall CSAT for the team is maintained and achieved.

•	Help resolve billing issues for customers.
I’ve been instrumental in deep diving and resolving billing issues for AWS customers in my previous role. I’d love to assist customers and provide a helping hand in terms of understanding the billing on their account, educating on how they can manage/optimize costs, to monitor their usage closely to avoid unexpected spike in their bills and so on.

•	Help train and onboard new support teammates.
I’ve been a head-trainer for New Hire batches entering the team in my previous role at AWS. I’ve always believed in knowledge sharing and would wish to share my experience and process expertise to the new hires in order to prepare them to go-live and maintain their core metrics.

•	Manage a support team.
I’ve always been a people person and would love to make sure my team is comfortable and have all the resources needed to carry out their day-to-day tasks efficiently. Would also love to conduct one-on-one sessions with my team to know each of them and to have the right expectations set regarding the process as well as how we can move forward/grow individually and as a team.

> Least Favourite Support Tasks:

•	Work with people to figure out if Vercel is suitable for their use case.
I believe this task needs to be carried out by the sales/pre-sales/account team in order to make sure they listen to the customer’s use case and suggest a resolution enabling the client to make use of Vercel’s products. And once the customer is on-boarded, we (support team) can continue assisting on other billing, technical issues that the client’s might face.

•	Engage multiple users at once in a public discussion, to answer their questions and troubleshoot problems.
Engaging multiple users/clients at once might cause chaos at times in terms of issues being different for different users. A forum to request the users to post their questions such that we as a team can take time, troubleshoot and get back to answering those questions asked, would be a better alternative.

•	Respond to queries on Twitter, Reddit, Hacker News and other 3rd party sites.
It would be most effective and impactful if the above task is performed by a dedicated Social Media team rather than it redirecting to the Customer Support team.

•	Find and recruit teammates for the support team.
Finding talents and recruiting them to join the support team is usually done by the HRBPs along with the higher leadership teams who decide on which candidate would suit the best to assist and resolve support related tasks.

•	Create video tutorials to help teach users a specific feature or use case.
Creating video tutorials heling users with a specific feature or use case would be time consuming if it is done as a part of a Support team’s task. Instead, we can have a dedicated team for preparing video tutorials and posting them on the internet for public use.

2) What do you want to learn or do more of at work?

- I'd love to join in and work on my day-to-day tasks efficiently to make sure the customer issue is resolved or moving towards resolution. I'd also make sure to meet the daily targets to keep up my performance metrics. Would work individually and as a team to help overall CSAT. I will also focus on career growth by contactly learning what I do not know and would also take up any extra responsibility that has been assigned and participate in process improvement activities.

3) Describe how you solved a challenge or technical issue that you faced in a previous role (preferably in a previous support role). How did you determine that your solution was successful?

- In my previous role, I had a customer reach out stating that he's unable to access his website and he mentioned he was losing customers because of this. I received a live chat from this customer and requested him to hold on while I look into the issue. Upon a review, I found that the customer's website was hosted on AWS EC2 and the associated instance was found to be in "stopped" state. Customer hadn't noticed that and reached out stating that it was AWS's fault. I got in touch with the EC2 service team via an internal ticket and requested that they troubleshoot this issue. The team responded back stating that the issue was because the instance is in "stopped" state. Once, the second opinion was received, I requested customer to start the instance by logging into his account. Customer tried that and it went back to "running" state and the instance state was healty. Within about 15 mins, the website was up and running. Customer appreciated the approach I had and the minimal time taken to resolve their issue and provided a postive rating for that support ticket and resolved it immediately.
  
4)  When would you choose to use Edge Functions, Serverless Functions, or Edge Middleware with Vercel?

- Edge Functions are ideal for fast, global compute tasks, Serverless Functions are better for complex compute tasks, and Edge Middleware is suitable for request and response manipulation at the edge.

5) Imagine a customer writes in requesting help with a build issue on a framework or technology that you've not seen before. How would you begin troubleshooting this and what questions would you ask the customer to understand the situation better?

- As a customer support engineer, when a customer writes in requesting help with a build issue on a framework or technology I'm not familiar with, I would follow a a step-by-step approach to troubleshoot the issue effectively. Here's how I would begin:

  . I would acknowledge the use case and clarify their ask. Eg: "Can you provide more details about the error message you're seeing?"
  
  . I would then try and gather as much information as possible. Eg: " Have you made any recent changes to your configurations?"
  
  . Next, I would ask about their OS and the the version of Node.js or other relevant tools that they've been using.
  
  . Once all details have been gathered, I would ask some time for my research around this error they're receiving. If I get to a potential resolution, I would revert back to the customer with the next steps. If not, will engage with my peers, other service teams for further troubleshooting to make sure the issue is ultimately resolved for the customer at the earliest.

6) The customer from question 5 replies to your response with the below:
“I’m so frustrated. I’ve been trying to make this work for hours and I just can’t figure it out. It must be a platform issue so just fix it for me instead of asking me questions.”
Please write a follow-up reply to the customer.

- Dear Customer,

Greetings for the day!

I understand you're concerned regarding the issue you've been experiencing and apologize for the inconvenience. I appreciate the time you've invested in trying to resolve the issue, and I'm here to help you find a resolution.

While I understand your request to fix the issue, I would need to clarify that troubleshooting often requires a collaborative effort to identify the root cause. This ensures that we address the problem effectively and provide the best resolution.

With that said, to better assist you, I'd like to ask a few more questions to narrow down the possible causes. This will help us provide a more targeted resolution. 

Could you please provide more details about the specific error messages you're seeing? Additionally, have you made any recent changes to your configuration or setup that might be related to the on-going issue?

Your cooperation and patience are greatly appreciated while we work on your concern. 

Appreciate your kind understanding and we look forward to hearing back from you soon! Take care. 

Best,

Divya

Vercel Support team.

7) A customer writes in to the Helpdesk asking "How do I do a redirect from the /blog path to https://example.com?" Please write a reply to the customer. Feel free to add any information about your decision making process after the reply.

- Hello Customer,

Greetings from Vercel Support team!

I see you'd like to know you could redirect from '/blog' path to 'https://example.com'. Please allow me to address your concerns.

To achieve this, you can use Vercel's built-in redirect feature. Here's how you can do it:

1. Using 'vercel.json':
2. 
   - In your 'vercel.json' file, add the following configuration:

     {
       "redirects": [
        {
           "source": "/blog",
           "destination": "https://example.com"
         }
       ]
     }
     
   - This will redirect any requests to '/blog' to 'https://example.com'.

If you have any further questions or need additional assistance, please don't hesitate to ask.

Appreciate your kind understanding and have a great day ahead! Take care. 

- I chose to provide 'vercel.json' since it was the easiest configuration and anybody could understand and follow.

8) A customer is creating a site and would like their project not to be indexed by search engines. Please write a reply to the customer. Feel free to add any information about your decision making process after the reply.

- Not sure about the approach here.

9) What do you think is one of the most common problems which customers ask Vercel for help with? How would you help customers to overcome common problems, short-term and long-term?

- One of the most common problems that I think customers ask Vercel for help with is related to errors and issues during deployment as I too faced issues in understanding the interface, such as unexpected errors etc. These issues can be frustrating and difficult to troubleshoot, especially for users who are new to Vercel.

To help customers overcome these common problems, both short-term and long-term, I would follow a structured approach:

> Short-term:
- Provide troubleshooting guides, Vercel's external/customer-facing documentations for customers to refer and get used to Vercel deployment.
- Direct customer to Vercel's forums/blog posts regarding the specific issue to make sure they can follow the exact steps outlined in the blogs.

> Long-term:
- Suggest any UI improvizations requesting the development teams to look into it for better understanding.
- Create a step-by-step process of initiating and deploying a project on Vercel and make videos and send it out to customers such that they can watch them at their convenience and get used to Vercel's interface.
- Would also raise a feature request to the internal development teams to look into any platform changes they can make in order to avoid customers running into errors mentioned.

10 How could we improve or alter this familiarisation exercise?

- The exercise was great however, for first time users, the UI seems a bit complicated in terms of attaching the content into the templates available and then deploying the project. The instructions/help links should have had example scenarios/videos of how a typical Vercel starter project would look like from start to finish.

Thank you.
