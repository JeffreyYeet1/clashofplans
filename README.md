## Clash of Plans 
Clash of Plans was inspired by the realization that while many task management and calendar applications exist, few effectively integrate these two essential productivity tools into a seamless experience. The name "Clash of Plans" playfully reflects the struggle of juggling competing priorities and time commitments while striving for productivity and efficiency.

## What it does
Clash of Plans is a **modern** web application designed to streamline productivity by seamlessly integrating task management and scheduling. It offers:
- A dynamic task management system with priority levels and duration tracking
- An interactive calendar with drag-and-drop event management
- Seamless interaction between tasks and calendar events
- Real-time updates for a smooth user experience
- A visually appealing, responsive UI with intuitive modals for effortless task and event management


## How we built it
The application is built using modern web technologies:
**Frontend Stack**
**Next.js:** delivers lightning-fast, server-rendered React with seamless navigation for an ultra-smooth user experience.
**TypeScript:** ensures rock-solid, type-safe code, eliminating runtime errors before they happen.
**Tailwind CSS:** provides sleek, responsive styling with utility-first magic for effortless design.

**Backend Stack**
**FastAPI:** powers a high-performance, async-driven backend with blazing-fast API responses.
**LangChain:** with RAG (Retrieval-Augmented Generation) supercharges AI-driven task automation with intelligent, context-aware insights. (Wrapper)
**Cohere:** AI Agent brings cutting-edge NLP to enhance user interactions with natural, fluid responses.
**Supabase:** acts as a real-time, scalable backend powerhouse, handling data storage and authentication effortlessly. 

## Challenges we ran into
One of the biggest challenges we faced was integrating UI/UX design while ensuring a seamless user experience without inadvertently mimicking platforms like Notion. Striking a balance between inspiration and originality was difficult.

Additionally, working as a team on this type of application was a new experience for us, which led to struggles in setting up and effectively utilizing CI/CD pipelines for streamlined development and deployment.

Furthermore, we encountered significant hurdles with new technologies such as Docker and Supabase. Since it was our first time using these tools, we faced various configuration and compatibility issues, which required extensive troubleshooting and learning on the go.

## Accomplishments that we're proud of
One of our biggest accomplishments was successfully integrating task management and calendar functionality into our experience. We created an intuitive drag-and-drop system that allows users to manage their schedules effortlessly while ensuring real-time updates for a smooth workflow. Additionally, designing a clean and responsive UI/UX was a huge milestone. We focused on balancing functionality and aesthetics, ensuring that users can easily navigate the platform while being visually appealing.

## What we learned
Throughout this project, we learned the importance of effective collaboration and version control, especially when working in a team environment. Using CI/CD pipelines helped streamline our deployment workflows, reinforcing best practices for software development.
We also gained hands-on experience with new technologies, such as Docker and Supabase. Understanding how to containerize applications and manage backend services efficiently was a crucial learning experience.
Moreover, integrating AI-powered features using LangChain and Cohere taught us how to leverage machine learning models for productivity tools. This opened up exciting possibilities for future enhancements.

## What's next for Clash of Plans
Moving forward, we plan to expand Clash of Plans' AI capabilities by introducing intelligent task prioritization and scheduling suggestions. By analyzing user habits, the application will be able to offer smart recommendations that optimize productivity. We also aim to enhance collaboration features, allowing users to create shared workspaces and receive real-time updates when working in teams. This will make Clash of Plans even more effective for group projects and professional use. Additionally, mobile support is a key priority. We want to ensure a seamless experience across all devices so users can manage their tasks and schedules on the go. Lastly, integrate more third-party APIs such as Gmail and Notion as an all-in-one application.
