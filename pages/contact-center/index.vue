<template>
  <div>
    <Head>
      <Title
        >Bizenforce - Call Center vs. Contact Center</Title
      >
      <Meta
        name="description"
        content="Call Center vs. Contact Center"
      />
    </Head>

    <section
      class="mx-auto md:max-w-7xl py-16 md:py-32 pb-3 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-6xl text-center py-8 md:text-7xl font-extrabold">
            Call Center vs. Contact Center: What's the Difference?
          </h1>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <div class="text-center text-xl pb-3">
            Source:
            <NuxtLink
              href="https://www.twilio.com/en-us/learn/contact-center/call-center-vs-contact-center"
              target="_blank"
              class="text-red-600 font-semibold"
              >Twilio</NuxtLink
            >
          </div>
          <p class="text-center md:text-xl text-gray-600">
            For many businesses, the call center is the heart of customer
            service. It's where customers call in for help and reps call out for
            sales. We refer to it as a “call center” because traditional
            customer service models rely on phone support as the main contact
            method. Today, however, call center agents interact with customers
            through a variety of channels. Thus, the call center has evolved
            into the contact center.
          </p>
        </div>
      </div>
    </section>
    <section>
      <div
        class="mx-auto md:max-w-7xl py-16 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div class="md:flex md:justify-between md:items-center md:space-x-10">
          <div class="w-full md:w-1/2 pb-5 md:pb-0">
            <h1 class="text-xl md:text-4xl font-bold pb-3">
              What is a call center?
            </h1>
            <p class="md:text-xl text-gray-600">
              Traditionally, a call center is an office where numerous agents
              provide customer service over the telephone. Inbound call centers
              receive calls for customer support and often serve as a knowledge
              base for tech support, billing questions, and more. These call
              centers focus on quick resolution times and agent productivity. In
              outbound call centers, agents make calls rather than receive them.
              These could be sales calls, marketing offers, surveys, fundraising
              requests, or debt collection, for example.
            </p>
          </div>
          <div class="w-full md:w-1/2">
            <img src="~/assets/twilio1.gif" alt="" class="w-full h-full" />
          </div>
        </div>
        <p class="md:text-xl text-gray-600 py-2">
          For customers, the term “call center” conjures an image of waiting on
          perpetual hold or being routed through an endless interactive voice
          response (IVR) system that never gives them what they need. Because so
          many consumers have had an experience along these lines, call centers
          have developed a bad rap. But as legacy phone systems give way to
          newer digital technologies, call centers are evolving.
        </p>
      </div>
    </section>

    <section class="bg-gray-900">
      <div
        class="mx-auto md:max-w-7xl py-16 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <h1 class="text-xl md:text-4xl font-bold text-white pb-3">
          What is a contact center?
        </h1>
        <p class="md:text-xl text-gray-200">
          The term “contact center” reflects that there are many ways to connect
          with a customer today besides by telephone. Increased customer
          expectations and newer technologies that allow for many communication
          channels created a shift in the traditional, decades-old call center
          model. Consumers want more ways to reach businesses, and businesses
          want new ways to improve customer experience.
        </p>
        <p class="md:text-xl text-gray-200 py-2">
          While call center agents generally focus on inbound and outbound
          calls, either on traditional phone lines or via Voice over Internet
          Protocol (VoIP), contact center agents handle a wide variety of
          communications. For example, in a multichannel contact center:
        </p>
        <ul class="list-disc pl-5">
          <li v-for="(ai, i) in ccExamples" :key="i" class="py-1 text-gray-100">
            {{ ai }}
          </li>
        </ul>
        <p class="md:text-xl text-gray-200 py-2">
          Companies usually integrate contact centers with customer relationship
          management (CRM) systems, where it’s easy to track, coordinate, and
          manage all interactions between the organization and the public.
        </p>
        <p class="md:text-xl text-gray-200 py-2">
          One challenge that contact centers face is that, depending on the
          infrastructure and ecosystem, it can be an alphabet soup of complex
          components. This occurs when companies purchase off-the-shelf systems
          or a highly customized network of technologies from multiple vendors.
          Some companies may even adopt a few cloud-based solutions, but the
          contact centers remain siloed from the rest of the company’s systems
          and can’t talk to each other. (More on the solution to this challenge
          below.)
        </p>
      </div>
    </section>

    <section
      class="mx-auto md:max-w-7xl py-16 pb-3 justify-center w-[100%] px-2 sm:px-6 lg:px-8"
    >
      <div>
        <div>
          <h1 class="text-3xl text-center py-8 md:text-5xl font-extrabold">
            The difference between call centers and contact centers
          </h1>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <div class="w-full md:max-w-4xl mx-auto">
            <p class="text-center md:text-xl text-gray-600 pb-3">
              The difference between a call center and a contact center comes
              down to the channels each uses. While call centers rely on legacy
              phone systems, contact centers leverage the many (often digital)
              channels customers use today to contact businesses.
            </p>
            <p class="text-gray-600 py-1">
              Customers now expect service and support from brands through an
              ever-expanding network of channels, contexts, and devices. They
              expect to connect in a similar way that they communicate with
              friends, from SMS to Snapchat. And they're willing to pay for it
              or take their business elsewhere if they don’t get it.
            </p>
            <p class="text-gray-600 py-1">
              Contact centers can provide this omnichannel approach and cut down
              on the time it takes to solve customers’ requests—whether they
              need help with a technical problem or placing a new
              order—regardless of the channel. This is critical, given that
              ultimately, the response time affects the bottom line. Customer
              surveys reveal that 86% of customers are willing to pay more for a
              product or service if it means they’ll get a better customer
              experience. In fact, they’re willing to pay 13% to 18% more. This
              is why 88% of businesses prioritize customer experience in contact
              centers.
            </p>
            <div>
              <img
                src="~/assets/twilio2.png"
                alt=""
                class="w-full h-full mx-auto max-w-[500px] max-h-[200px]"
              />
            </div>
            <p class="text-gray-600 py-1">
              So why do so many businesses fail to take contact centers to the
              next level of customer experience? In most cases, companies want
              to keep up with changing user behavior and emerging channels, but
              existing infrastructure holds them back. However, this is slowly
              changing as more businesses adopt cloud-based solutions for
              customer experience. According to Dimension Data, 36.3% of
              organizations now have cloud solutions for contact centers, and
              this number will double to 71.9% in the coming year.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="my-16">
      <div
        class="mx-auto md:max-w-7xl justify-center w-[100%] px-2 sm:px-6 lg:px-8"
      >
        <div>
          <h1 class="text-3xl text-center py-8 md:text-5xl font-extrabold">
            Legacy contact center infrastructure
          </h1>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <div class="w-full md:max-w-4xl mx-auto">
            <p class="text-center md:text-xl text-gray-600 pb-3">
              Many businesses built contact centers using products designed
              nearly a decade ago. This is a lifetime in the digital age. For
              example, a system launched in 2009 likely began with a request for
              proposal (RFP) and vendor evaluations in 2007. Given the product
              development cycles for contact center hardware and software, the
              product proposed by a chosen vendor in 2007 was probably first
              released in 2004 and initially designed 5 years before that.
            </p>
            <p class="text-gray-600">
              This is how many companies currently find themselves caught in the
              trap of an aging and costly infrastructure that impedes progress.
              Contact center systems currently in place were expensive and
              time-consuming to install and customize, so businesses are,
              understandably, reluctant to update them.
            </p>

            <div>
              <img
                src="~/assets/twilio3.png"
                alt=""
                class="w-full h-full mx-auto max-w-[500px] max-h-[300px]"
              />
            </div>
            <p class="text-gray-600 py-1">
              So why do so many businesses fail to take contact centers to the
              next level of customer experience? In most cases, companies want
              to keep up with changing user behavior and emerging channels, but
              existing infrastructure holds them back. However, this is slowly
              changing as more businesses adopt cloud-based solutions for
              customer experience. According to Dimension Data, 36.3% of
              organizations now have cloud solutions for contact centers, and
              this number will double to 71.9% in the coming year.
            </p>
            <p class="text-gray-600">
              How often have you called into an IVR and heard, “Please listen
              carefully because the menu options have recently changed,” and
              knew that the menu actually hasn't changed in a very long time?
              That’s because most legacy IVR systems take an average of 9 months
              of professional services to make even the smallest changes.
            </p>
            <p class="text-gray-600">
              It's difficult to experiment, iterate, and improve a contact
              center under those circumstances. In the meantime, customer
              expectations continue to change rapidly as new technologies and
              communication channels become the norm. When aging infrastructure
              can’t keep pace with customers and the communications technologies
              they rely on, the result is frustrated customers and agents, along
              with wasted time and resources.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="mt-16 bg-gray-900">
      <div
        class="mx-auto md:max-w-7xl justify-center w-[100%] px-2 pt-6 pb-10 sm:px-6 lg:px-8"
      >
        <div>
          <h1
            class="text-3xl text-white text-center py-8 md:text-5xl font-extrabold"
          >
            Modern contact center solutions
          </h1>
          <div class="w-16 mx-auto border-t-4 border-blue-600 mb-8 mt-2"></div>
          <div class="w-full md:max-w-4xl mx-auto">
            <p class="text-center md:text-xl text-gray-100 pb-3">
              Today, a new approach to the traditional call center is available
              that allows businesses to deliver the caliber of real-time
              customer experience necessary to win in increasingly competitive
              markets. Instead of taking an off-the-shelf system from a telecom
              vendor and accepting inflexible systems with a monolithic feature
              set, this agile contact center software approach enables companies
              to build the exact solution needed when the companies need it.
              It’s an approach that offers more than updated technology—it
              reenvisions how to design and build contact center operations.
            </p>
            <p class="text-gray-200">
              Two main factors drive the evolution of the call center: digital
              innovation and the resulting changes in customer behavior.
              According to a 2020 Dimension Data report, most organizations
              engage with customers via 8 different channels, and 23.2% say an
              omnichannel approach is the driving force behind the customer
              journey design strategy.
            </p>
            <p class="text-gray-200">
              Customers want companies to communicate with them on their
              prefered channel—whether it’s phone, SMS, or Facebook Messenger.
              And the proliferation of digital channels doesn’t lessen the
              importance of the call center. In fact, the opposite is true.
              People still want to connect with other people at the other end of
              an interaction.
            </p>
            <p class="text-gray-200">
              Integration is the key to creating an experience that leaves
              customers feeling like the service is just for them. When an IVR
              (or agent) knows the entire customer journey—the pages they've
              looked at, the products they’ve purchased, their billing
              situation, etc.—it greatly improves the customer experience.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
const ccExamples = [
  "Technical support is delivered over in-app chat or video.",
  "Order status updates are delivered via SMS.",
  "Event promotions are sent as push notifications.",
  "Surveys are deployed over Facebook Messenger.",
  "Sales inquiries received by email are sent directly to an agent to connect by phone.",
];
</script>
