<template>
  <div>
    <Head>
      <Title
        >Bizenforce - Supervised, Unsupervised, and Re-enforcement
        Learning</Title
      >
      <Meta
        name="description"
        content="Supervised, Unsupervised, and Re-enforcement Learning"
      />
    </Head>
    <section
      class="mx-auto md:max-w-7xl py-16 md:py-32 md:pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-4xl text-center py-8 md:text-7xl font-extrabold">
            Machine Learning
          </h1>
          <p class="text-gray-600 text-md md:text-2xl text-center">
            <span class="font-bold italic">Machine learning</span> is a subfield
            of artificial intelligence that involves the use of algorithms and
            statistical models to enable computers to learn from and make
            predictions or decisions based on input data. In other words, it is
            a method of teaching computers to recognize patterns in data and use
            those patterns to make predictions or take actions without being
            explicitly programmed to do so.
          </p>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <p class="text-gray-600 text-md text-center">
            Machine learning algorithms can be supervised, unsupervised, or
            re-enforcement learning.
          </p>
        </div>
      </div>
    </section>

    <section>
      <div class="mx-auto md:max-w-7xl w-[100%] px-2 sm:px-6 lg:px-8">
        <div>
          <img
            src="~/assets/ml1.jpeg"
            alt=""
            class="w-full mx-auto max-w-[600px] h-full max-h-[250px]"
          />
        </div>
      </div>
    </section>

    <section>
      <div class="mx-auto md:max-w-7xl w-[100%] px-2 sm:px-6 lg:px-8">
        <div
          class="md:flex md:space-x-10 md:justify-between md:items-center py-8"
        >
          <div class="w-full">
            <h1 class="text-3xl py-8 md:text-7xl font-extrabold">
              Supervised Learning
            </h1>
            <p class="text-gray-600">
              Supervised learning is a type of machine learning where the
              algorithm is trained on a labeled dataset. In supervised learning,
              the input data is fed to the algorithm along with the
              corresponding output or target variable. The algorithm learns to
              predict the output variable by analyzing the relationship between
              the input data and the output data.
            </p>
            <p class="text-gray-600">
              Examples of supervised learning include:
            </p>
            <ul class="list-decimal pl-5">
              <li
                v-for="(ai, i) in supervisedLearnings"
                :key="i"
                class="py-1 text-gray-600"
              >
                <span class="font-bold">{{ ai.title }}</span
                >: {{ ai.subtitle }}
              </li>
            </ul>
            <p class="text-gray-600 py-2">
              In all these examples, the algorithm is trained on a labeled
              dataset to learn the relationship between the input and output
              variables. Once the algorithm is trained, it can predict the
              output variable for new, unseen input data.
            </p>
          </div>
          <div class="w-full md:w-1/2">
            <img
              src="../../assets/sl1.png"
              alt="Bizenforce AI Tips"
              class="max-h-[500px] rounded"
            />
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="mx-auto md:max-w-7xl w-[100%] px-2 sm:px-6 lg:px-8 py-8">
        <h1 class="text-3xl text-center py-8 md:text-7xl font-extrabold">
          Unsupervised Learning
        </h1>
        <p class="text-gray-600 text-center">
          Unsupervised learning is a type of machine learning where the
          algorithms learn from unlabeled data without any explicit feedback or
          guidance from a teacher or supervisor. In other words, the algorithm
          tries to identify patterns and structure in the data on its own,
          without any prior knowledge of what it is looking for. The goal of
          unsupervised learning is to find hidden or unknown patterns in the
          data and represent them in a way that can be easily understood.
        </p>
        <p class="text-gray-600 text-center py-2 font-bold">
          Examples of supervised learning include:
        </p>
        <div class="md:flex md:space-x-10 md:justify-between md:items-center">
          <div class="w-full md:w-1/2">
            <img
              src="../../assets/usl1.png"
              alt="Bizenforce AI Tips"
              class="max-h-[500px] rounded w-full"
            />
          </div>
          <div class="w-full">
            <ul class="list-decimal pl-5">
              <li
                v-for="(ai, i) in unsupervisedLearnings"
                :key="i"
                class="py-1 text-gray-600"
              >
                <span class="font-bold">{{ ai.title }}</span
                >: {{ ai.subtitle }}
              </li>
            </ul>
            <p class="text-gray-600 py-2">
              Overall, unsupervised learning is useful for discovering hidden
              patterns and relationships in data, which can then be used to
              inform decision-making and improve business outcomes.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="mx-auto md:max-w-7xl w-[100%] px-2 sm:px-6 lg:px-8 py-8">
        <h1 class="text-3xl py-8 md:text-7xl font-extrabold">
          Reinforcement learning (RL)
        </h1>
        <div class="md:flex md:space-x-10 md:justify-between md:items-center">
          <div class="w-full">
            <p class="text-gray-600">
              Reinforcement learning (RL) is a type of machine learning in which
              an agent learns to make decisions by interacting with an
              environment. The agent receives feedback in the form of rewards or
              penalties based on its actions, and it uses this feedback to learn
              which actions are most likely to lead to a desired outcome.
            </p>
            <p class="text-gray-600">
              Examples of supervised learning include:
            </p>
            <ul class="list-decimal pl-5">
              <li
                v-for="(ai, i) in reenforcementLearnings"
                :key="i"
                class="py-1 text-gray-600"
              >
                <span class="font-bold">{{ ai.title }}</span
                >: {{ ai.subtitle }}
              </li>
            </ul>
            <p class="text-gray-600 py-2">
              Overall, RL has a wide range of applications in fields such as
              gaming, robotics, finance, and more.
            </p>
          </div>
          <div class="w-full md:w-1/2">
            <img
              src="../../assets/rl1.webp"
              alt="Bizenforce AI Tips"
              class="max-h-[500px] rounded"
            />
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="mx-auto md:max-w-7xl w-[100%] px-2 sm:px-6 lg:px-8 py-8">
        <h1 class="text-3xl py-8 text-center md:text-7xl font-extrabold">
          The Five Machine Learning Steps
        </h1>
        <p class="text-gray-600 text-md md:text-2xl text-center">
          Irrespective of the particular model or training algorithm employed,
          machine learning experts follow a consistent workflow to execute
          machine learning tasks. This process involves iterative steps, where
          you assess progress at each stage. If things are not going according
          to plan, you should go back and re-examine the current or previous
          steps to pinpoint where the problem lies
        </p>
        <div class="md:flex md:space-x-10 md:justify-between md:items-center">
          <div class="w-full">
            <ul class="list-decimal pl-5 my-3">
              <li
                v-for="(ai, i) in mlSteps"
                :key="i"
                class="py-1 text-gray-600"
              >
                <span class="font-bold">{{ ai.title }}</span
                >: {{ ai.subtitle }}
              </li>
            </ul>
          </div>
          <div class="w-full md:w-1/2">
            <img
              src="~/assets/mlstep.jpeg"
              alt="Bizenforce AI Tips"
              class="max-h-[500px] rounded"
            />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts" setup>
const supervisedLearnings = [
  {
    title: "Classification",
    subtitle:
      "Predicting whether an email is spam or not. The input data could be the email message and the output variable could be a binary variable (spam or not spam).",
  },
  {
    title: "Regression",
    subtitle:
      "Predicting the price of a house based on its features such as the number of bedrooms, bathrooms, and location. The input data could be the features of the house and the output variable could be a continuous variable (the price of the house)",
  },
  {
    title: "Image Recognition",
    subtitle:
      "Recognizing handwritten digits. The input data could be an image of a digit and the output variable could be the corresponding label (0-9)",
  },
  {
    title: "Sentiment analysis",
    subtitle:
      "Predicting whether a movie review is positive or negative. The input data could be the movie review and the output variable could be a binary variable (positive or negative sentiment)",
  },
  {
    title: "Fraud Detection",
    subtitle:
      "Identifying fraudulent credit card transactions. The input data could be the transaction details and the output variable could be a binary variable (fraudulent or not fraudulent)",
  },
];

const unsupervisedLearnings = [
  {
    title: "Clustering",
    subtitle:
      "This involves grouping similar data points together based on their characteristics. For example, clustering can be used to group customers based on their purchasing behavior, or to group documents based on their content",
  },
  {
    title: "Dimensionality Reduction",
    subtitle:
      "This involves reducing the number of features or variables in a dataset while retaining the important information. This can help simplify the data and make it easier to analyze. An example of this is Principal Component Analysis (PCA)",
  },
  {
    title: "Anomaly Detection",
    subtitle:
      "This involves identifying rare or unusual data points in a dataset. For example, anomaly detection can be used to detect fraudulent transactions in financial data or to identify unusual patterns in network traffic",
  },
  {
    title: "Association Rule Learning",
    subtitle:
      "This involves finding relationships between variables in a dataset. For example, association rule learning can be used to find items that are frequently purchased together in a grocery store",
  },
];
const reenforcementLearnings = [
  {
    title: "Playing games",
    subtitle:
      "RL algorithms have been used to train agents to play games such as chess, Go, and Atari games. In these games, the agent receives a reward for winning or progressing to the next level, and a penalty for losing",
  },
  {
    title: "Robotics",
    subtitle:
      "RL has been used to train robots to perform tasks such as grasping objects, navigating through environments, and even playing table tennis. In these scenarios, the agent receives rewards for completing the task correctly and penalties for errors",
  },
  {
    title: "Advertising",
    subtitle:
      "RL has been used to optimize online advertising campaigns. In this case, the agent learns which ads to show to which users in order to maximize the number of clicks or conversions",
  },
  {
    title: "Finance",
    subtitle:
      "RL has been used to develop trading strategies for financial markets. The agent learns which trades to make based on market conditions and historical data, with the goal of maximizing profits",
  },
];

const mlSteps = [
  {
    title: "Define the problem",
    subtitle:
      "Defining the problem in machine learning (ML) involves identifying and formulating the task that the ML system should perform. It is a crucial step in the ML workflow as it lays the foundation for the entire project.",
  },
  {
    title: "Build the dataset",
    subtitle:
      "Building the dataset in machine learning (ML) involves collecting and preparing the data that will be used to train the ML model. It is a crucial step in the ML workflow as the quality of the dataset significantly affects the accuracy and effectiveness of the resulting ML model",
  },
  {
    title: "Train the model",
    subtitle:
      "Training the model in machine learning (ML) involves teaching the model to recognize patterns and relationships within the data. It is a critical step in the ML workflow as the accuracy and effectiveness of the resulting ML model depend on how well it is trained",
  },
  {
    title: "Evaluate the model",
    subtitle:
      "Evaluating the model in machine learning (ML) involves assessing the model's performance and effectiveness in making accurate predictions or classifications on new, unseen data. It is a crucial step in the ML workflow as it helps determine the model's strengths and weaknesses and identify areas for improvement.",
  },
  {
    title: "Inference (use the model)",
    subtitle:
      "Inference in machine learning (ML) refers to the process of applying a trained model to new, unseen data to make predictions or classifications. It is the phase in the ML workflow where the model is used to make real-world decisions or recommendations based on the knowledge it has gained during the training phase.",
  },
];
</script>
