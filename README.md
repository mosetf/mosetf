### Moses Abwova
Backend engineer. [Portfolio](https://abwova-portfolio.vercel.app) · Nairobi, Kenya

---

#### What I do

I build Django backends for real usage, not demos. The difference matters when your API handles traffic from people who have no idea what Django is and don't need to.

Most of my actual work lives in the things that are easy to skip: token rotation that actually invalidates, RBAC that doesn't become middleware spaghetti, and migrations you can run on a Thursday without holding your breath.

#### What I'm good at

Django past the tutorial stage. Custom user models, middleware chains, signals. The parts that tutorials gloss over because explaining them cleanly is hard.

Databases. I probably spend more time on schema design than is normal. Foreign key strategies, when to denormalize, whether to index now or wait. A good schema makes the application layer simpler. A bad one means every new feature starts with a migration argument.

Security beyond `@login_required`. JWT rotation with blacklisting. Role-based access that holds up past three or four roles. APIs where secure is the default.

#### Stack

![Python](https://img.shields.io/badge/Python-1a1a1a?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-1a1a1a?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a1a1a?style=flat-square&logo=postgresql&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-1a1a1a?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-1a1a1a?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1a1a1a?style=flat-square&logo=docker&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-1a1a1a?style=flat-square&logo=websocket&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-1a1a1a?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-1a1a1a?style=flat-square&logo=next.js&logoColor=white)

#### What I'm learning

CropAI, a crop yield prediction system, is live: XGBoost for prediction, a LoRA fine-tuned Qwen model with FAISS retrieval for recommendations, deployed on Azure. Shipping it forced me to figure out what actually happens when you embed a model in a Django app.

The model itself was the easy part. Data pipelines, versioning, inference latency. And handling the case where the model is wrong and the user needs to know that. That's the part I'm still working through.

#### Working with me

I argue about schemas before writing application code. Edge cases get tested because I've been burned. And I'd rather ship something simple that works than something clever that might not. The goal is code the next person can read without a walkthrough.

---

#### Get in touch

[stanlym315@gmail.com](mailto:stanlym315@gmail.com)
