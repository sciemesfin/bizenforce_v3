<template>
  <div>
    <Head>
      <Title
        >Bizenforce - A new phase of the internet that leverages decentralized technologies, such as blockchain, to create a more open, transparent, and secure internet</Title
      >
      <Meta
        name="description"
        content="A new phase of the internet that leverages decentralized technologies, such as blockchain, to create a more open, transparent, and secure internet"
      />
    </Head>
    <section
      class="mx-auto md:max-w-7xl py-16 md:py-32 md:pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-6xl text-center pt-8 md:text-7xl font-extrabold">
            Web 3.0
          </h1>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <p class="text-gray-600 text-md md:text-2xl text-center">
            <span class="font-bold italic">Web3, also known as Web 3.0</span>
            or the decentralized web, is a term used to describe the evolution
            of the World Wide Web from its current centralized state to a more
            decentralized and democratized ecosystem. It refers to a set of
            technologies and protocols that enable peer-to-peer transactions and
            interactions without thes need for intermediaries.
          </p>
          <p class="text-gray-600 text-center">
            In the context of blockchain technology, Web3 refers to the use of
            decentralized networks, such as Ethereum, to create a more open,
            transparent, and secure web. This includes the use of decentralized
            applications (DApps) that run on blockchain networks, decentralized
            identity systems, and the ability to store and transfer value
            without the need for traditional financial institutions.
          </p>
          <p class="text-gray-600 text-center">
            In essence, Web3 is about creating a more decentralized, democratic,
            and user-controlled internet where individuals have more control
            over their data and digital identity, and where applications and
            services are not owned or controlled by a single entity.
          </p>
        </div>
      </div>
    </section>

    <section class="bg-gray-100">
      <div></div>
      <div>
        <div
          class="mx-auto md:max-w-7xl py-16 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
        >
          <h1 class="font-extrabold text-center text-2xl md:text-6xl pb-10">
            Web1.0 vs Web2.0 vs Web3.0
          </h1>
          <p class="text-center text-lg md:text-xl tetx-gray-600">
            The World Wide Web has gone through three stages of evolution:
            Web1.0, Web2.0, and Web3.0. Web1.0 was the early, read-only web
            where websites were static and lacked interactivity. Web2.0 emerged
            in the early 2000s and was characterized by interactive and
            collaborative websites that encouraged user-generated content.
            Web3.0 is the next stage, known as the semantic or intelligent web,
            which will use advanced technologies like AI and blockchain to
            create a more intelligent, machine-readable web. Each stage of the
            web has brought new opportunities for communication, collaboration,
            and innovation.
          </p>
        </div>
        <div class="w-full">
          <img src="~/assets/webs.png" alt="" class="h-full w-full" />
        </div>
        <div
          class="mx-auto md:max-w-7xl py-16 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
        >
          <div class="md:flex md:items-center md:justify-between md:space-x-10">
            <div class="w-full grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-10">
              <div v-for="(web, i) in webs" :key="i" class="py-2">
                <h2 class="font-bold text-xl pb-1">Web{{ i + 1 }}.0</h2>
                <p class="text-gray-600">{{ web }}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div
        class="mx-auto md:max-w-7xl py-16 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <p class="text-gray-900 text-md md:text-2xl pb-10 text-center">
          Web3.0 has the potential to significantly influence the world by
          creating a more decentralized, transparent, and secure web. Here are a
          few ways in which it could have an impact:
        </p>
        <div class="py-2 grid grid-cols-1 md:grid-cols-2 gap-4">
          <div
            v-for="(ai, i) in web3Impacts"
            :key="i"
            class="border border-gray-100 h-full rounded p-5 hover:bg-gray-100"
          >
            <div class="flex items-center h-full">
              <div>
                <h2 class="font-semibold text-xl md:text-2xl py-2 text-center">
                  {{ ai.title }}
                </h2>
                <p class="text-center text-gray-600">{{ ai.subtitle }}.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
const web3Impacts: any = [
  {
    title: "Democratizing access",
    subtitle:
      "Web3.0 can enable people to have more control over their digital identity and data, giving them the ability to share or withhold it as they see fit. This could help to reduce the power imbalance between large corporations and individuals, making it easier for people to access services and opportunities",
  },
  {
    title: "Facilitating trust",
    subtitle:
      "Web3.0 is built on blockchain technology, which provides a secure and transparent way to track transactions and interactions. This could help to increase trust in online interactions, particularly in areas such as e-commerce, where fraud and identity theft are major concerns",
  },
  {
    title: "Encouraging innovation",
    subtitle:
      "Web3.0 enables the development of decentralized applications (DApps) that can operate independently of centralized servers. This creates a fertile ground for innovation, as developers can create new applications that are not limited by the constraints of traditional web infrastructure",
  },
  {
    title: "Creating new business models",
    subtitle:
      "Web3.0 could enable new business models that are more decentralized and community-driven. For example, decentralized marketplaces could allow buyers and sellers to transact directly with each other, without the need for intermediaries",
  },
];

const webs = [
  `Web1.0, also known as the "read-only web," refers to the early days of the internet when websites were static and lacked interactivity. During this time, the primary function of websites was to provide information to users. The content was mostly created by businesses and organizations, and there was no way for users to contribute or collaborate.`,
  `Web2.0, also known as the "read-write web," emerged in the early 2000s and represented a shift towards more interactive and collaborative websites. This stage of the web was characterized by the rise of social media, blogging platforms, and other web applications that allowed users to create, share, and interact with content. Web2.0 websites encouraged user-generated content and provided tools for social networking, sharing, and collaboration.`,
  `Web3.0, also known as the "semantic web" or "intelligent web," is the next stage in the evolution of the web. It is characterized by a move towards a more intelligent, machine-readable web, where data is organized and linked in a way that allows computers to understand it better. This will enable advanced applications such as personalized search engines, virtual personal assistants, and other intelligent agents that can assist users in various tasks. Web3.0 will also incorporate new technologies such as artificial intelligence, blockchain, and decentralized systems.`,
];
</script>
