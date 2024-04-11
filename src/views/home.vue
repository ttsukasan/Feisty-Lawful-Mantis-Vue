<template>
  <div class="home-container"
    ><div class="home-header"
      ><header
        data-thq="thq-navbar"
        class="navbarContainer home-navbar-interactive"
        ><span class="logo">枠ぽん</span
        ><div data-thq="thq-navbar-nav" class="home-desktop-menu"
          ><nav class="home-links"></nav
          ><div class="home-buttons"
            ><button class="home-login buttonFlat">Login</button
            ><button class="buttonFilled">Register</button></div
          ></div
        ><div data-thq="thq-burger-menu" class="home-burger-menu"
          ><svg viewBox="0 0 1024 1024" class="home-icon socialIcons">
            <path
              d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
            ></path></svg></div
        ><div data-thq="thq-mobile-menu" class="home-mobile-menu1 mobileMenu"
          ><div class="home-nav"
            ><div class="home-top"
              ><span class="logo">BOOKMARKLET</span
              ><div data-thq="thq-close-menu" class="home-close-menu"
                ><svg viewBox="0 0 1024 1024" class="home-icon02 socialIcons">
                  <path
                    d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                  ></path></svg></div></div
            ><nav class="home-links1"
              ><span class="home-nav12 bodySmall">Home</span
              ><span class="home-nav22 bodySmall">Features</span
              ><span class="home-nav32 bodySmall">Download</span
              ><span class="home-nav42 bodySmall">Support</span
              ><span class="home-nav52 bodySmall">Blog</span></nav
            ><div class="home-buttons1"
              ><button class="buttonFlat">Login</button
              ><button class="buttonFilled">Register</button></div
            ></div
          ><div
            ><svg
              viewBox="0 0 950.8571428571428 1024"
              class="home-icon04 socialIcons"
            >
              <path
                d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
              ></path></svg
            ><svg
              viewBox="0 0 877.7142857142857 1024"
              class="home-icon06 socialIcons"
            >
              <path
                d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
              ></path></svg
            ><svg
              viewBox="0 0 602.2582857142856 1024"
              class="home-icon08 socialIcons"
            >
              <path
                d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
              ></path></svg></div></div></header></div
    ><div class="home-hero"
      ><div class="home-hero1 heroContainer"
        ><div class="home-container01"
          ><h1 class="home-hero-heading heading1"
            >ブラウザ上で図形やテキストを描画</h1
          ><span class="home-hero-sub-heading bodyLarge"
            ><span
              ><span
                ><span>Bookmarklet Application Distribution</span
                ><span> <span v-html="rawezob"></span></span></span
              ><span
                ><span> <span v-html="raw71is"></span></span
                ><span> <span v-html="rawsdid"></span></span></span></span
            ><span
              ><span
                ><span> <span v-html="rawlugf"></span></span
                ><span> <span v-html="rawjfbh"></span></span></span
              ><span
                ><span> <span v-html="rawm5yw"></span></span
                ><span>
                  <span
                    v-html="raw3j8s"
                  ></span></span></span></span></span></div></div></div
    ><div class="home-features"
      ><div class="featuresContainer"
        ><div class="home-features1"
          ><div class="home-container02"
            ><span class="overline"><span>features</span><br /></span
            ><h2 class="home-features-heading heading2"
              >Discover the Power of Our Bookmarklet Application</h2
            ><span class="home-features-sub-heading bodyLarge"
              ><span
                ><span
                  ><span
                    >Enhance your browsing experience with these amazing
                    features</span
                  ><span> <span v-html="rawue7u"></span></span></span
                ><span
                  ><span> <span v-html="rawg8oh"></span></span
                  ><span> <span v-html="rawvrlt"></span></span></span></span
              ><span
                ><span
                  ><span> <span v-html="rawz0qp"></span></span
                  ><span> <span v-html="rawalmi"></span></span></span
                ><span
                  ><span> <span v-html="raw3xen"></span></span
                  ><span>
                    <span
                      v-html="rawvpgw"
                    ></span></span></span></span></span></div
          ><div class="home-container03"
            ><feature-card
              heading="ああああああああ"
              subHeading="Easily save your favorite websites with just one click"
            ></feature-card
            ><feature-card
              heading="Organize Bookmarks"
              subHeading="Effortlessly manage and categorize your saved bookmarks"
            ></feature-card
            ><feature-card
              heading="Sync Across Devices"
              subHeading="Access your bookmarks from any device with seamless synchronization"
            ></feature-card
            ><feature-card
              heading="Customize Settings"
              subHeading="Tailor the bookmarklet application to suit your browsing preferences"
            ></feature-card></div></div></div></div
    ><div class="home-pricing"
      ><div class="pricingContainer"
        ><div class="home-container04"
          ><span class="overline"><span>Pricing</span><br /></span
          ><h2 class="heading2">Choose Your Plan</h2
          ><span class="home-pricing-sub-heading bodyLarge"
            ><span
              ><span
                >Upgrade to unlock more features and enhance your browsing
                experience</span
              ></span
            ></span
          ></div
        ><div class="home-container05"
          ><div class="freePricingCard home-pricing-card"
            ><div class="home-container06"
              ><span class="home-text36 heading3">Free</span
              ><span class="bodySmall"
                >Get started with our basic features for free</span
              ></div
            ><div class="home-container07"
              ><span class="home-text37"><span>$</span><span></span></span
              ><span class="home-free-plan-price">0</span></div
            ><div class="home-container08"
              ><div class="home-container09"
                ><span class="home-text40">✔</span
                ><span class="bodySmall"
                  >Access to basic bookmarklet functionality</span
                ></div
              ><div class="home-container10"
                ><span class="home-text41">✔</span
                ><span class="bodySmall"
                  >Save up to 10 bookmarks per month</span
                ></div
              ><div class="home-container11"
                ><span class="home-text42">✔</span
                ><span class="bodySmall">Limited customization options</span></div
              ><div class="home-container12"
                ><span class="home-text43">✔</span
                ><span class="bodySmall">Email support</span></div
              ></div
            ><button class="home-button buttonOutline"
              >Continue with Free</button
            ></div
          ><div class="basicPricingCard home-pricing-card1"
            ><div class="home-container13"
              ><span class="home-text44 heading3">BASIC</span
              ><span class="bodySmall"
                >Upgrade to unlock more features and customization</span
              ></div
            ><div class="home-container14"
              ><span class="home-text45"><span>$</span><span></span></span
              ><span class="home-basic-plan-pricing">5</span
              ><span class="home-text48">/ month</span></div
            ><div class="home-container15"
              ><div class="home-container16"
                ><span class="home-text49">✔</span
                ><span class="bodySmall">All features of FREE plan</span></div
              ><div class="home-container17"
                ><span class="home-text51">✔</span
                ><span class="bodySmall">Unlimited bookmark saving</span></div
              ><div class="home-container18"
                ><span class="home-text52">✔</span
                ><span class="bodySmall"
                  >Customizable bookmark categories</span
                ></div
              ><div class="home-container19"
                ><span class="home-text53">✔</span
                ><span class="bodySmall">Priority email support</span></div
              ><div class="home-container20"
                ><span class="home-text54">✔</span
                ><span class="bodySmall">Basic analytics dashboard</span></div
              ></div
            ><button class="home-button1 buttonFilledSecondary"
              >Try the Basic plan</button
            ></div
          ><div class="proPricingCard home-pricing-card2"
            ><div class="home-container21"
              ><span class="home-text55 heading3"><span>PRO</span><br /></span
              ><span class="bodySmall"
                >Go Pro for advanced features and premium support</span
              ></div
            ><div class="home-container22"
              ><span class="home-text58"><span>$</span><span></span></span
              ><span class="home-pro-plan-pricing">10</span
              ><span class="home-text61">/ month</span></div
            ><div class="home-container23"
              ><div class="home-container24"
                ><span class="home-text62">✔</span
                ><span class="bodySmall"> All features of BASIC plan</span></div
              ><div class="home-container25"
                ><span class="home-text64">✔</span
                ><span class="bodySmall"
                  >Advanced analytics and insights</span
                ></div
              ><div class="home-container26"
                ><span class="home-text65">✔</span
                ><span class="bodySmall">Custom branding options</span></div
              ><div class="home-container27"
                ><span class="home-text66">✔</span
                ><span class="bodySmall">24/7 priority support</span></div
              ><div class="home-container28"
                ><span class="home-text67">✔</span
                ><span class="bodySmall"
                  >Integration with third-party apps</span
                ></div
              ></div
            ><button class="home-button2 buttonFilledSecondary"
              >Try the PRO plan</button
            ></div
          ></div
        ></div
      ></div
    ><div class="home-banner"
      ><div class="bannerContainer home-banner1"
        ><h1 class="home-banner-heading heading2"
          >Enhance Your Browser with Our Bookmarklet Apps</h1
        ><span class="home-banner-sub-heading bodySmall"
          ><span
            ><span
              ><span
                >Discover our innovative bookmarklet applications designed to
                streamline your browsing activities. Whether you&apos;re a casual
                user or a power browser, our tools cater to your needs. With
                seamless integration and user-friendly interfaces, take your
                browsing experience to the next level.</span
              ><span> <span v-html="rawrry6"></span></span></span
            ><span
              ><span> <span v-html="raw9rro"></span></span
              ><span> <span v-html="raw25k1"></span></span></span></span
          ><span
            ><span
              ><span> <span v-html="raw4da0"></span></span
              ><span> <span v-html="rawyidw"></span></span></span
            ><span
              ><span> <span v-html="rawat0u"></span></span
              ><span> <span v-html="raw3yg4"></span></span></span></span></span
        ><button class="buttonFilled">Learn More</button></div
      ></div
    ><div class="home-faq"
      ><div class="faqContainer"
        ><div class="home-faq1"
          ><div class="home-container29"
            ><span class="overline"><span>FAQ</span><br /></span
            ><h2 class="home-text85 heading2">Common questions</h2
            ><span class="home-text86 bodyLarge"
              ><span>Here are some of the most common questions that we get.</span
              ><br /></span></div
          ><div class="home-container30"
            ><app-question1
              answer="A bookmarklet is a small piece of JavaScript code that can be saved as a bookmark in your browser to add functionality or perform specific actions on a webpage."
              question="What is a bookmarklet?"
            ></app-question1
            ><app-question1
              answer="To install the bookmarklet, simply click on the download button next to the type of application you are using, and follow the instructions provided."
              question="How do I install the bookmarklet?"
            ></app-question1
            ><app-question1
              answer="The bookmarklet application is compatible with most modern browsers, but it may have limitations on certain older or less common browsers."
              question="Can I use the bookmarklet on any browser?"
            ></app-question1
            ><app-question1
              answer="Yes, the bookmarklet application is free to download and use for personal and non-commercial purposes."
              question="Is the bookmarklet application free to use?"
            ></app-question1
            ><app-question1
              answer="While the bookmarklet application comes with predefined functionality, advanced users can customize the JavaScript code to tailor it to their specific needs."
              question="Can I customize the bookmarklet functionality?"
            ></app-question1></div></div></div></div
    ><div class="home-footer"
      ><footer class="footerContainer home-footer1"
        ><div class="home-container31"
          ><span class="logo">BOOKMARKLET</span
          ><nav class="home-nav1"
            ><span class="bodySmall">Home</span
            ><span class="home-nav221 bodySmall">Features</span
            ><span class="home-nav321 bodySmall">Download</span
            ><span class="home-nav421 bodySmall">Support</span
            ><span class="home-nav521 bodySmall">Blog</span></nav
          ></div
        ><div class="home-separator"></div
        ><div class="home-container32"
          ><span class="bodySmall home-text89"
            >© 2023 myCompany, All Rights Reserved.</span
          ><div class="home-icon-group1"
            ><svg
              viewBox="0 0 950.8571428571428 1024"
              class="home-icon10 socialIcons"
            >
              <path
                d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
              ></path></svg
            ><svg
              viewBox="0 0 877.7142857142857 1024"
              class="home-icon12 socialIcons"
            >
              <path
                d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
              ></path></svg
            ><svg
              viewBox="0 0 602.2582857142856 1024"
              class="home-icon14 socialIcons"
            >
              <path
                d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
              ></path></svg></div></div></footer></div
  ></div>
</template>

<script>
import FeatureCard from '../components/feature-card'
import AppQuestion1 from '../components/question1'

export default {
  name: 'Home',
  props: {},
  components: {
    FeatureCard,
    AppQuestion1,
  },
  data() {
    return {
      rawezob: ' ',
      raw71is: ' ',
      rawsdid: ' ',
      rawlugf: ' ',
      rawjfbh: ' ',
      rawm5yw: ' ',
      raw3j8s: ' ',
      rawue7u: ' ',
      rawg8oh: ' ',
      rawvrlt: ' ',
      rawz0qp: ' ',
      rawalmi: ' ',
      raw3xen: ' ',
      rawvpgw: ' ',
      rawrry6: ' ',
      raw9rro: ' ',
      raw25k1: ' ',
      raw4da0: ' ',
      rawyidw: ' ',
      rawat0u: ' ',
      raw3yg4: ' ',
    }
  },
  metaInfo: {
    title: 'Feisty Lawful Mantis',
    meta: [
      {
        property: 'og:title',
        content: 'Feisty Lawful Mantis',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-header {
  width: 100%;
  display: flex;
  z-index: 100;
  position: fixed;
  align-items: center;
  flex-direction: column;
  background-color: var(--dl-color-gray-white);
}
.home-desktop-menu {
  flex: 1;
  display: flex;
  justify-content: space-between;
}
.home-links {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-buttons {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-login {
  margin-right: 32px;
}
.home-burger-menu {
  display: none;
}
.home-icon {
  width: var(--dl-size-size-xsmall);
  cursor: pointer;
  height: var(--dl-size-size-xsmall);
}
.home-mobile-menu1 {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: absolute;
  flex-direction: column;
  justify-content: space-between;
}
.home-nav {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-top {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.home-close-menu {
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-icon02 {
  width: var(--dl-size-size-xsmall);
  cursor: pointer;
  height: var(--dl-size-size-xsmall);
}
.home-links1 {
  flex: 0 0 auto;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
}
.home-nav12 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav22 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav32 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav42 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav52 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-buttons1 {
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-hero {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  margin-top: 96px;
  align-items: flex-start;
  justify-content: center;
}
.home-hero1 {
  align-items: center;
  justify-content: center;
}
.home-container01 {
  gap: var(--dl-space-space-oneandhalfunits);
  height: 72px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-hero-heading {
  width: 798px;
  max-width: 800px;
  text-align: center;
}
.home-hero-sub-heading {
  font-size: 18px;
  text-align: center;
}
.home-features {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-features1 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  justify-content: flex-start;
}
.home-container02 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-features-heading {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-features-sub-heading {
  font-size: 18px;
  text-align: center;
}
.home-container03 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-oneandhalfunits);
  grid-template-columns: 1fr 1fr;
}
.home-pricing {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-container04 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-pricing-sub-heading {
  text-align: center;
}
.home-container05 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.home-container06 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text36 {
  text-transform: uppercase;
}
.home-container07 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-text37 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-free-plan-price {
  font-size: 4rem;
  font-weight: 700;
}
.home-container08 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
}
.home-container09 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text40 {
  line-height: 150%;
}
.home-container10 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text41 {
  line-height: 150%;
}
.home-container11 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text42 {
  line-height: 150%;
}
.home-container12 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text43 {
  line-height: 150%;
}
.home-button {
  width: 100%;
}
.home-container13 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text44 {
  text-transform: uppercase;
}
.home-container14 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-text45 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-basic-plan-pricing {
  font-size: 4rem;
  font-weight: 700;
}
.home-text48 {
  font-size: 1.15rem;
  font-style: normal;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-container15 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-container16 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text49 {
  line-height: 150%;
}
.home-container17 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text51 {
  line-height: 150%;
}
.home-container18 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text52 {
  line-height: 150%;
}
.home-container19 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text53 {
  line-height: 150%;
}
.home-container20 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text54 {
  line-height: 150%;
}
.home-button1 {
  width: 100%;
}
.home-container21 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text55 {
  text-transform: uppercase;
}
.home-container22 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-text58 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-pro-plan-pricing {
  font-size: 4rem;
  font-weight: 700;
}
.home-text61 {
  font-size: 1.15rem;
  font-style: normal;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-container23 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
}
.home-container24 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text62 {
  line-height: 150%;
}
.home-container25 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text64 {
  line-height: 150%;
}
.home-container26 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text65 {
  line-height: 150%;
}
.home-container27 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text66 {
  line-height: 150%;
}
.home-container28 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text67 {
  line-height: 150%;
}
.home-button2 {
  width: 100%;
}
.home-banner {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-banner-heading {
  text-align: center;
}
.home-banner-sub-heading {
  max-width: var(--dl-size-size-maxwidth);
  margin-top: var(--dl-space-space-twounits);
  text-align: center;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-faq {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-faq1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: flex-start;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-fourunits);
}
.home-container29 {
  display: flex;
  max-width: 35%;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text85 {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text86 {
  text-align: left;
}
.home-container30 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-footer {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-container31 {
  gap: var(--dl-space-space-unit);
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-nav1 {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
}
.home-nav221 {
  margin-left: var(--dl-space-space-unit);
}
.home-nav321 {
  margin-left: var(--dl-space-space-unit);
}
.home-nav421 {
  margin-left: var(--dl-space-space-unit);
}
.home-nav521 {
  margin-left: var(--dl-space-space-unit);
}
.home-separator {
  flex: 0 0 auto;
  width: 100%;
  height: 0px;
  display: flex;
  margin-top: var(--dl-space-space-twounits);
  align-items: flex-start;
  margin-left: 0px;
  border-color: var(--dl-color-gray-900);
  border-style: solid;
  border-width: 1px;
  margin-right: 0px;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
}
.home-container32 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-icon-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-icon10 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
}
.home-icon12 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
}
.home-icon14 {
  width: 24px;
  height: 24px;
}
@media(max-width: 991px) {
  .home-hero1 {
    flex-direction: column;
  }
  .home-container01 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .home-hero-heading {
    text-align: center;
  }
  .home-hero-sub-heading {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-features-sub-heading {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-pricing-sub-heading {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-container05 {
    align-items: center;
    flex-direction: column;
  }
  .home-pricing-card {
    width: 100%;
    padding: var(--dl-space-space-twounits);
    max-width: 450px;
  }
  .home-pricing-card1 {
    width: 100%;
    max-width: 450px;
  }
  .home-pricing-card2 {
    width: 100%;
    max-width: 450px;
  }
  .home-banner-sub-heading {
    max-width: 100%;
  }
  .home-text86 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 767px) {
  .home-navbar-interactive {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-desktop-menu {
    display: none;
  }
  .home-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .home-nav12 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav22 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav32 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav42 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav52 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-hero1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-hero-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-features1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-features-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-container03 {
    grid-template-columns: 1fr;
  }
  .home-pricing-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-container05 {
    align-items: center;
    flex-direction: column;
  }
  .home-pricing-card {
    width: 100%;
    max-width: 450px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-pricing-card1 {
    width: 100%;
    max-width: 450px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-pricing-card2 {
    width: 100%;
    max-width: 450px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .home-banner1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-banner-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-faq1 {
    flex-direction: column;
  }
  .home-container29 {
    max-width: 100%;
    align-self: center;
    align-items: center;
    justify-content: center;
  }
  .home-text86 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-footer1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-container32 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .home-text89 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .home-navbar-interactive {
    padding: var(--dl-space-space-unit);
  }
  .home-mobile-menu1 {
    padding: 16px;
  }
  .home-hero1 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container01 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-features1 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-pricing-card2 {
    margin-bottom: 0px;
  }
  .home-banner1 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-footer1 {
    padding: var(--dl-space-space-unit);
  }
  .home-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-container32 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .home-text89 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
