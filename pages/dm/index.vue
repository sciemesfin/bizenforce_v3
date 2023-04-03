<template>
  <div>
    <Head>
      <Title
        >Bizenforce - Outbound vs Inbound marketing</Title
      >
      <Meta
        name="description"
        content="Outbound vs Inbound marketing"
      />
    </Head>

    <section
      class="mx-auto md:max-w-7xl py-16 md:py-32 md:pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-6xl text-center pt-8 md:text-7xl font-extrabold">
            Digital Marketing
          </h1>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <p class="text-gray-600 text-md md:text-2xl text-center">
            <span class="font-bold italic">Digital marketing</span>
            is the practice of promoting and selling products or services using
            digital technologies. It involves leveraging digital channels such
            as search engines, social media platforms, email, websites, mobile
            applications, and other online platforms to reach and engage with
            potential customers.
          </p>
        </div>
      </div>
    </section>

    <section class="bg-gray-900">
      <div
        class="mx-auto md:max-w-7xl pt-6 pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div>
          <h1
            class="text-3xl text-white text-center pt-8 pb-3 md:text-5xl font-extrabold"
          >
            What is Outbound Marketing?
          </h1>
          <p class="text-gray-200 text-lg md:text-xl text-center py-2">
            Outbound marketing is a traditional marketing strategy that involves
            reaching out to potential customers and promoting products or
            services through various channels such as television commercials,
            radio ads, print advertisements, billboards, direct mail,
            telemarketing, and email marketing. The main aim of outbound
            marketing is to create brand awareness, generate leads, and
            ultimately drive sales by interrupting a potential customer's daily
            routine and getting their attention.
          </p>
          <p class="text-gray-200 text-lg md:text-xl text-center py-2">
            Outbound marketing is often contrasted with inbound marketing, which
            involves creating valuable content and experiences that attract
            potential customers to the brand, rather than actively reaching out
            to them. While outbound marketing can still be effective in certain
            industries and situations, many companies have shifted their focus
            to inbound marketing in recent years, as it has been shown to be
            more cost-effective and have a higher ROI (return on investment).
          </p>
        </div>
      </div>
    </section>

    <section>
      <div
        class="mx-auto md:max-w-7xl pt-6 pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div>
          <h1
            class="text-3xl text-gray-900 text-center pt-8 pb-3 md:text-5xl font-extrabold"
          >
            What is Inbound Marketing?
          </h1>
          <p class="text-gray-600 text-lg md:text-xl text-center py-2">
            Inbound marketing is a marketing strategy that focuses on attracting
            customers to a business through the creation of valuable content and
            experiences that align with the customer's interests and needs. The
            goal of inbound marketing is to build trust and credibility with
            potential customers, establish a strong brand presence, and
            ultimately drive sales by attracting and converting leads.
          </p>
          <p class="text-gray-600 text-lg md:text-xl text-center py-2">
            Inbound marketing typically involves creating and distributing
            content such as blog posts, social media posts, videos, podcasts,
            whitepapers, and webinars that provide helpful information or
            insights to potential customers. This content is designed to address
            the questions and concerns of the target audience, positioning the
            brand as a trusted authority in its industry.
          </p>
          <p class="text-gray-600 text-lg md:text-xl text-center py-2">
            In addition to content creation, inbound marketing also involves
            optimizing a company's website for search engines, creating targeted
            landing pages for specific campaigns, and using email marketing and
            social media to build relationships with potential customers.
          </p>
          <p class="text-gray-600 text-lg md:text-xl text-center py-2">
            Compared to outbound marketing, inbound marketing is typically more
            cost-effective and has a higher ROI, as it focuses on building
            relationships with potential customers rather than interrupting
            their daily routines with ads or cold calls.
          </p>
        </div>
      </div>
    </section>

    <section class="bg-gray-900">
      <div
        class="mx-auto md:max-w-7xl pt-6 pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div class="w-full m">
          <h1
            class="text-3xl text-white text-center pt-8 pb-3 md:text-5xl font-extrabold"
          >
            Comparison of Outbound and Inbound Marketing
          </h1>
          <p class="text-gray-200 text-lg md:text-xl text-center py-2">
            Outbound and inbound marketing are two different approaches to
            promoting a product or service. Outbound marketing involves reaching
            out to potential customers through traditional marketing channels,
            while inbound marketing involves creating valuable content that
            attracts customers to a business.
          </p>
          <div class="py-2 grid grid-cols-1 md:grid-cols-4 gap-4">
            <div
              v-for="(ai, i) in comparisions"
              :key="i"
              class="border border-gray-800 h-full rounded p-5 bg-gray-600 hover:bg-blue-600 hover:shadow"
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
          <p class="text-gray-200 text-lg text-center py-2">
            In summary, outbound and inbound marketing have different
            approaches, focus, communication, cost, control, effectiveness, and
            metrics. Depending on the goals and resources of the business, both
            approaches can be effective in promoting a product or service.
          </p>
        </div>
      </div>
    </section>

    <section>
      <div
        class="mx-auto md:max-w-7xl pt-6 pb-10 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div>
          <h1
            class="text-3xl text-gray-900 text-center pt-8 pb-3 md:text-5xl font-extrabold"
          >
            Affiliate marketing ?
          </h1>
          <p class="text-gray-600 text-lg md:text-xl text-center py-2">
            Affiliate marketing is a type of performance-based marketing in
            which a business rewards one or more affiliates for each customer
            brought about by the affiliate's marketing efforts. Essentially,
            affiliate marketing involves a partnership between a business and an
            affiliate, who promotes the business's products or services to their
            own audience.
          </p>
          <p class="text-gray-600">
            The affiliate earns a commission or other form of compensation for
            each customer they refer to the business. This compensation can be a
            percentage of the sale, a flat fee per customer, or another
            agreed-upon arrangement.
          </p>
          <p class="py-2">
            Affiliate marketing typically involves four key players:
          </p>
          <ul class="list-decimal pl-5">
            <li
              v-for="(ai, i) in affiliatePlayers"
              :key="i"
              class="py-1 text-gray-600"
            >
              <span class="font-bold">{{ ai.title }}</span
              >: {{ ai.subtitle }}
            </li>
          </ul>
          <p class="text-gray-600 mt-2">
            To become an affiliate marketer, individuals or organizations can
            sign up for an affiliate program offered by a merchant or join an
            affiliate network that offers multiple programs. They can then
            promote the merchant's product or service through various channels,
            such as their website, blog, social media, email marketing, or paid
            advertising.
          </p>
          <p class="text-gray-600">
            Affiliate marketing can be a mutually beneficial arrangement for
            both the merchant and the affiliate, as it allows the merchant to
            reach a wider audience and the affiliate to earn additional income
            through their marketing efforts.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts" setup>
const comparisions = [
  {
    title: "Approach",
    subtitle: `Outbound marketing is a more traditional approach where businesses reach out to potential customers, while inbound marketing is a more modern approach where businesses attract potential customers`,
  },
  {
    title: "Focus",
    subtitle: `Outbound marketing focuses on promoting a product or service, while inbound marketing focuses on building a relationship with the customer`,
  },
  {
    title: "Communication",
    subtitle: `Outbound marketing involves one-way communication, where the business is the sender and the customer is the receiver. In contrast, inbound marketing involves two-way communication, where the business and the customer communicate with each other.`,
  },
  {
    title: "Cost",
    subtitle: `Outbound marketing can be expensive because it often involves paid advertising, while inbound marketing can be less expensive because it focuses on creating valuable content that attracts customers`,
  },
  {
    title: "Control",
    subtitle: `Outbound marketing gives the business more control over the message and who receives it, while inbound marketing gives the customer more control over the information they receive`,
  },
  {
    title: "Effectiveness",
    subtitle: `Outbound marketing can be effective in reaching a large audience quickly, but it may not be as effective in converting those leads into customers. Inbound marketing may take longer to build an audience, but it can be more effective in converting leads into customers because it involves building a relationship with the customer.`,
  },
  {
    title: "Metrics",
    subtitle: `Outbound marketing is often measured in terms of reach and impressions, while inbound marketing is measured in terms of engagement and conversion rates.`,
  },
  {
    title: "Targeting",
    subtitle: ` Outbound marketing casts a wide net in the hopes of reaching as many potential customers as possible, while inbound marketing is more targeted towards specific audiences who are more likely to be interested in the product or service.`,
  },
];

const affiliatePlayers = [
  {
    title: "The Merchant",
    subtitle: "This is the business that offers the product or service.",
  },
  {
    title: "The Affiliate",
    subtitle:
      "This is the individual or organization that promotes the merchant's product or service.",
  },
  {
    title: "The Network",
    subtitle:
      "This is the platform or system that manages the affiliate program, tracks sales, and facilitates payments.",
  },
  {
    title: "The Customer",
    subtitle: "This is the person who purchases the product or service.",
  },
];
</script>
