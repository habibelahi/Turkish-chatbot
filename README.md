Chatbots, software programs facilitating communication between humans through natural language, are increasingly relevant in the fields of Natural Language Processing (NLP) and Artificial Intelligence (AI). Despite advancements in AI, the development of an effective chatbot remains a significant challenge. A successful chatbot must not only understand user input but also provide appropriate responses. This paper introduces TrBot, the first Turkish deep-learning chatbot developed for general context use, employing the seq2seq model and designed to engage in text-based conversations with users on various topics. TrBot's architecture was constructed and evaluated using popular seq2seq model architectures, trained on two distinct datasets: a QA dataset containing 40,702 entries and a conversation dataset with 304,446 entries. Notably, these datasets were manually generated without the use of handcrafted rules. The model underwent training on a powerful computer, producing impressive results wherein TrBot successfully replicated correct answers to a majority of inquiries, achieving 80% accuracy in the QA dataset and 70% in the Dialog dataset. As the first Turkish chatbot developed for general usage, this paper outlines the design, training, and evaluation process of TrBot, shedding light on its performance and potential applications in real-world scenarios.

Step 1: Install the required libraries
Step 2: Clone the project
Step 3: Train the model python main.py --batch-size 32 --num-epochs 1000 -lr 0.001
Step 4: Run the model python app.py 
