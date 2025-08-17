Jenkins Freestyle Demo 

This project is a simple demo of Jenkins Freestyle jobs with job chaining.

 Jobs Overview

Job-A → runs first and produces an artifact.

Job-B → copies artifact from Job-A (via Copy Artifact Plugin) and triggers Job-C.

Job-C → final job, processes the result.

⚙️ Setup

Install Jenkins and Copy Artifact Plugin.

Create jobs Job-A, Job-B, Job-C.

Configure Post-build Actions to chain jobs:

Job-A → Job-B → Job-C

▶️ Run

Start Job-A → Jenkins will run the chain automatically.

 Goal

Learn the basics of Freestyle Projects, artifacts, and job chaining.
