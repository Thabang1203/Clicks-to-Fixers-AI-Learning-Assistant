# Clicks to Fixers — AI Concept Chatbot

[**CAPACITI Tech Career Accelerator | Group Project | April 2026**](https://claude.ai/public/artifacts/6d526a6c-c8a6-4c91-8c2f-26ec3b0ea10e)

**Group Members:** Thabang Norman Lesotho, Zama Bhengane, Sibongiseni Magutshwa, Lungile Princess Nzimande, Zizipo Malangeni

---

## What We Built

Clicks to Fixers is an interactive AI concept learning assistant built for the CAPACITI Tech Career Accelerator practical project. It's a fully custom web application that covers all required topic areas from Modules 1–4 of the bootcamp. Rather than using a third-party no-code platform like Dialogflow or Botpress, we built this as a self-contained web app using standard web technologies — HTML5, CSS3, and vanilla JavaScript.

## Why We Built It This Way

We chose a custom approach for several reasons. Full UI control lets us design rich multimedia experiences — inline diagrams, quiz cards, colour-coded responses — that no-code platforms restrict. The project costs zero money since there are no API fees, rate limits, or subscriptions; it runs entirely client-side and can be hosted free on GitHub Pages. Deployment is instant — a single HTML file on any static host gives us a public URL immediately. Building from scratch better represents our group's data engineering background than configuring a drag-and-drop tool. The chatbot functions offline once loaded, making it accessible in low-bandwidth South African environments. And we built a multi-pass keyword and word-overlap scoring engine that's functionally equivalent to Dialogflow intent classifiers.

## The 20 Q&A Pairs We Implemented

We covered core terminology across all four modules. From Module 1, we explain what Artificial Intelligence is, the AI vs ML vs Deep Learning hierarchy, real-world AI applications, AI in healthcare, and AI in finance. From Module 2, we cover Machine Learning, overfitting and underfitting, reinforcement learning, and supervised learning. From Module 3, we cover Deep Learning, Natural Language Processing, real-world NLP applications, key challenges in NLP, neural networks, Large Language Models, computer vision, and GANs. From Module 4, we cover AI ethics overview, bias in AI, and privacy considerations including POPIA.

## The Conversation Flows We Designed

We built five guided conversation flows. The NLP flow walks through the definition of NLP, then real-world NLP applications, then key challenges in NLP. The AI Ethics flow covers the ethics overview, bias in AI, and privacy considerations. The AI vs ML vs Deep Learning flow starts with what AI is, then what Machine Learning is, then the hierarchy that ties them together. The Neural Networks flow goes from what a neural network is, to what deep learning is, to what LLMs are. The Computer Vision flow covers computer vision, then deep learning, then real-world AI applications.

Each flow is triggered from the left sidebar. After Step 1 loads, chip buttons for Step 2 and Step 3 appear automatically above the input bar, guiding the user through the complete path without re-typing.

## Technical Specifications

Every bot response includes "Related" concept buttons that chain to further Q&As on the same topic — supporting three or more follow-up questions per topic. Every response also includes a green "Further Learning" box recommending the specific CAPACITI bootcamp module to study next. Each of our 20 Q&A pairs is tagged to a specific module and cited in the response footer with the full module name. The "Related" buttons on every response connect concepts — for example, Neural Networks links to Deep Learning, Backpropagation, and Activation Functions. Unrecognised queries return a friendly "I didn't quite catch that" message with five topic suggestion buttons and sidebar guidance. And every bot response includes thumbs-up and thumbs-down helpful buttons — when clicked, a confirmation message replaces the buttons.

## The Multimedia Elements We Added

We built five multimedia elements directly into the chat interface. The AI/ML/Deep Learning hierarchy shows a nested node diagram with AI containing ML containing Deep Learning, using colour-coded levels and explanatory notes. The neural network architecture visual shows input, hidden, and output layers with colour-coded nodes and role labels. The NLP processing pipeline is a six-step annotated flow from raw text input through tokenisation, preprocessing, to output. The AI ethics framework is a six-pillar grid covering fairness, transparency, privacy, safety, accountability, and inclusivity. And we built an interactive quiz with eight randomised multiple-choice questions, instant correct or wrong visual feedback, and a full explanation per answer. All diagrams are rendered inline in the chat window using HTML and CSS — no static images or external files required.

## How We Aligned With Evaluation Criteria

For accuracy of AI concept explanations, which carried 30 percent weighting, we wrote all 20 Q&A pairs to CAPACITI Module standards with structured explanations and key term highlighting. For conversational flow naturalness at 20 percent weighting, we built five guided flows with chip-based step progression and related concept buttons that maintain natural conversation. For handling edge case questions at 15 percent weighting, our multi-pass intent matching engine handles rephrased questions and returns a friendly error response with suggestions. For feedback mechanism implementation at 10 percent weighting, we added thumbs-up and thumbs-down buttons on every bot response with confirmation messages on click. For quality of technical documentation at 15 percent weighting, we produced this document covering all required sections with tables, flows, screenshots, and coverage summary. For multimedia integration at 10 percent weighting, we delivered four inline diagrams plus one interactive quiz — that's five multimedia elements, exceeding the minimum requirement of three diagrams plus one interactive element.

## Knowledge Base Coverage Summary

We exceeded the requirement of 15 Q&A pairs with 20 total. We have 11 pairs covering core terminology including ML, NLP, LLMs, neural networks, and computer vision — well beyond what was needed. We have two pairs covering AI versus ML versus Deep Learning distinctions. We have four pairs covering real-world applications across industries. And we have three pairs covering basic ethical considerations. Every topic area is fully covered.

## What Our Screenshots Show

Our screenshots document the welcome screen, a bot response with the further learning box, a diagram rendered inline in the chat, the quiz with answer feedback, and the error handling response showing the fallback for unrecognised queries — "I didn't quite catch that" with five suggestion buttons.
