<template>
  <div>
    <Head>
      <Title
        >Bizenforce - Power your business with a decentralized digital ledger technology that records transactions in a secure and transparent way.</Title
      >
      <Meta
        name="description"
        content="Power your business with a decentralized digital ledger technology that records transactions in a secure and transparent way"
      />
    </Head>
    <section
      class="mx-auto md:max-w-7xl py-16 md:py-32 md:pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-6xl text-center py-8 md:text-7xl font-extrabold">
            Blockchain
          </h1>
          <p class="text-gray-600 text-md md:text-2xl text-center">
            <span class="font-bold italic">Blockchain</span>
            is a decentralized digital ledger technology that records
            transactions in a secure and transparent way. It consists of a
            network of nodes that verify and store transaction records in a
            secure and tamper-proof manner.
          </p>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <p class="text-gray-600 text-md text-center">
            Each block in the blockchain contains a cryptographic hash of the
            previous block, making it difficult to modify past transactions.
            This makes the blockchain an immutable record of all transactions
            that have ever taken place on the network.
          </p>
          <p class="text-gray-600 text-md text-center">
            One of the most well-known implementations of blockchain technology
            is the cryptocurrency Bitcoin, which uses the blockchain to record
            all transactions made using the currency. However, blockchain
            technology has a wide range of potential applications beyond
            cryptocurrency, such as supply chain management, voting systems, and
            digital identity verification.
            <NuxtLink
              class="text-blue-600"
              target="_blank"
              href="https://en.wikipedia.org/wiki/Blockchain"
              >Read more
            </NuxtLink>
          </p>
        </div>
      </div>
    </section>

    <section class="bg-gray-900">
      <div
        class="mx-auto md:max-w-7xl py-16 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div>
          <h1
            class="font-extrabold text-white text-center text-2xl md:text-6xl"
          >
            How Blockchain works?
          </h1>
          <p class="text-gray-100 text-center py-3">
            Blockchain is a distributed ledger technology that allows multiple
            parties to maintain a shared database of transactions without the
            need for a central authority or intermediary. Here is a simplified
            explanation of how blockchain works:
          </p>
          <div class="py-2 grid grid-cols-1 md:grid-cols-4 gap-4">
            <div
              v-for="(ai, i) in howItWorks"
              :key="i"
              class="border border-gray-800 h-full rounded p-5 hover:bg-gray-600 hover:shadow"
            >
              <div class="flex items-center h-full">
                <div>
                  <h2
                    class="font-semibold text-xl py-2 text-center text-gray-200"
                  >
                    {{ i + 1 }}. {{ ai.title }}
                  </h2>
                  <p class="text-center text-sm text-gray-300">
                    {{ ai.subtitle }}.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div>
            <p class="text-center text-lg py-3 text-gray-200">
              Overall, blockchain technology provides a secure and decentralized
              way of recording and verifying transactions, making it useful for
              a wide range of applications, including cryptocurrency, supply
              chain management, and digital identity verification.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section
      class="mx-auto md:max-w-7xl justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-3xl text-center py-8 md:text-7xl font-extrabold">
            What is a cryptocurrency?
          </h1>
          <p class="text-gray-600 text-md md:text-2xl text-center">
            <span class="font-bold italic">Crypto</span>
            (short for cryptocurrency) is a new form of digital money powered by
            cryptography.
          </p>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <div class="py-2">
            <div
              class="md:flex md:space-x-10 md:justify-center md:items-center"
            >
              <div class="w-full md:max-w-[350px] md:max-h-[350px]">
                <img
                  src="~/assets/crypto.png"
                  alt="cryptocurrency"
                  class="w-full h-full"
                />
              </div>
              <div class="w-full md:w-1/2">
                <p class="text-gray-600">
                  It all started in 2008 with Bitcoin. You could use it to send
                  funds to anyone anywhere globally. What made crypto different
                  from normal bank transfers or other financial services like
                  Paypal or Alipay is that there was no middleman for the first
                  time.
                </p>
                <p class="py-2">Wait, what is a middleman?</p>
                <p class="text-gray-600">
                  A middleman is a central authority like a bank or government
                  that intervenes in a transaction between the sender and
                  recipient. They have the power to surveill, censor or revert
                  transactions and they can share the sensitive data they
                  collect about you with third parties. They also often dictate
                  which financial services you have access to.
                </p>
                <p class="text-gray-600">
                  Things are different with crypto. Transactions directly
                  connect sender and recipient without having to deal with any
                  central authority. Nobody else will have access to your funds
                  and nobody can tell you what services you can use. This is
                  possible because of the blockchain technology upon which
                  cryptocurrencies operate.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-gray-900">
      <div
        class="mx-auto md:max-w-7xl py-16 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div>
          <h1
            class="font-extrabold text-white md:text-center text-4xl md:text-6xl"
          >
            What is a smart contract ?
          </h1>
          <p class="text-gray-100 md:text-center text-xl py-3">
            A smart contract is a computer program that automatically executes
            the terms of a contract when certain predetermined conditions are
            met. It is a self-executing contract that operates on a blockchain
            network, allowing for secure and transparent execution of
            contractual agreements without the need for intermediaries.
            <NuxtLink href="https://ethereum.org/en/smart-contracts/" target="_blank"
            class="text-blue-600"
            >Learn more</NuxtLink>
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
const howItWorks = [
  {
    title: "Transactions are initiated",
    subtitle:
      "Transactions can be anything of value, such as money, data, or assets, that are initiated by a user.",
  },
  {
    title: "Transaction is verified",
    subtitle:
      "The transaction is then verified by a network of computers called nodes, using complex algorithms that ensure the transaction is valid",
  },
  {
    title: "Transaction is bundled into a block",
    subtitle:
      "Once the transaction is verified, it is bundled with other verified transactions into a block",
  },
  {
    title: "Block is added to the blockchain",
    subtitle:
      "The block is then added to the existing blockchain, which is a chain of blocks linked together using cryptography",
  },
  {
    title: "Consensus is reached",
    subtitle:
      "To ensure the integrity of the blockchain, the network of nodes must reach a consensus on the validity of the block before it can be added to the chain.",
  },
  {
    title: "Block is validated",
    subtitle:
      "Once the consensus is reached, the block is validated and added to the blockchain.",
  },
  {
    title: "Block is immutable",
    subtitle:
      "Once a block is added to the blockchain, it becomes immutable, meaning it cannot be altered or deleted. This creates a transparent and tamper-proof record of all transactions on the blockchain",
  },
  {
    title: "Participants are rewarded",
    subtitle:
      "Participants in the network, called miners, are rewarded for verifying transactions and adding new blocks to the chain",
  },
];
</script>
