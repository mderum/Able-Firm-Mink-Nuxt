<template>
  <div class="home-container">
    <div class="home-header">
      <header data-thq="thq-navbar" class="home-navbar-interactive">
        <span class="home-logo">
          DogeXGrok
          <span v-html="raw16sd"></span>
        </span>
        <div data-thq="thq-navbar-nav" class="home-desktop-menu">
          <nav class="home-links">
            <span>Token Supply</span>
            <span class="home-nav2">Roadmap</span>
            <span class="home-nav3">Partners</span>
            <span class="home-nav4">Disclaimer</span>
            <span class="home-nav5">Blog</span>
          </nav>
          <div class="home-buttons">
            <button class="home-login button">Login</button>
            <button class="home-register button">Register</button>
          </div>
        </div>
        <div data-thq="thq-burger-menu" class="home-burger-menu">
          <svg viewBox="0 0 1024 1024" class="home-icon">
            <path
              d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
            ></path>
          </svg>
        </div>
        <div data-thq="thq-mobile-menu" class="home-mobile-menu">
          <div class="home-nav">
            <div class="home-top">
              <span class="home-logo1">CRYPTO</span>
              <div data-thq="thq-close-menu" class="home-close-menu">
                <svg viewBox="0 0 1024 1024" class="home-icon02">
                  <path
                    d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                  ></path>
                </svg>
              </div>
            </div>
            <nav class="home-links1">
              <span class="home-nav11">Token Supply</span>
              <span class="home-nav21">Roadmap</span>
              <span class="home-nav31">Partners</span>
              <span class="home-nav41">Disclaimer</span>
              <span class="home-nav51">Blog</span>
            </nav>
            <div class="home-buttons1">
              <button class="home-login1 button">Login</button>
              <button class="home-register1 button">Register</button>
            </div>
          </div>
          <div>
            <svg viewBox="0 0 950.8571428571428 1024" class="home-icon04">
              <path
                d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
              ></path></svg
            ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon06">
              <path
                d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
              ></path></svg
            ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon08">
              <path
                d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
              ></path>
            </svg>
          </div>
        </div>
      </header>
    </div>
    <div class="home-hero">
      <div class="home-hero1">
        <div class="home-container01">
          <h1 class="home-hero-heading heading1">THE HOTEST GROK KING IS HERE</h1>
          <span class="home-hero-sub-heading">BUY NOW</span>
          <div class="home-btn-group">
            <button class="home-hero-button2 button">
              CA: 0x29CB847F63c0dab7f08587792A60dB71B2d8a704
            </button>
          </div>
        </div>
      </div>
    </div>
    <div class="home-details">
      <div class="home-details1">
        <div class="home-container02">
          <span class="home-text sectionTitle">
            <span>Details</span>
            <br />
          </span>
          <h2 class="home-details-heading heading2">Roadmap</h2>
          <span class="home-details-sub-heading">
            Discover our roadmap for success
          </span>
        </div>
        <div class="home-details-image">
          <span class="home-text03">
            <span>DogeXGrok</span>
            <span class="home-text05"><span v-html="rawcoiy"></span></span>
          </span>
        </div>
      </div>
    </div>
    <div class="home-features">
      <div class="home-features-container">
        <div class="home-features1">
          <div class="home-container03">
            <h2 class="home-features-heading heading2">Tokenomics</h2>
            <span class="home-features-sub-heading">
              Discover the powerful features of our crypto currency platform.
            </span>
          </div>
          <div class="home-container04">
            <feature-card
              Heading="Secure Transactions"
              SubHeading="All transactions are encrypted and secure, ensuring the safety of your funds."
            ></feature-card>
            <feature-card
              Heading="Fast and Efficient"
              SubHeading="Our crypto currency platform offers lightning-fast transactions, allowing you to transfer funds quickly and efficiently."
            ></feature-card>
            <feature-card
              Heading="Decentralized Network"
              SubHeading="Our crypto currency operates on a decentralized network, providing transparency and eliminating the need for intermediaries."
            ></feature-card>
            <feature-card
              Heading="Global Accessibility"
              SubHeading="With our crypto currency, you can access your funds from anywhere in the world, making it convenient for international transactions."
            ></feature-card>
          </div>
        </div>
      </div>
    </div>
    <div class="home-pricing">
      <div class="home-pricing1">
        <div class="home-container05">
          <h2 class="home-pricing-heading heading2">Roadmap</h2>
          <span class="home-pricing-sub-heading">
            Unlock the power of cryptocurrency with our flexible pricing options
          </span>
        </div>
        <div class="home-container06">
          <div class="home-pricing-card">
            <div class="home-container07">
              <span class="home-text06 heading3">Free</span>
              <span class="home-free-plan-description">
                Get started with our free plan
              </span>
            </div>
            <div class="home-container08">
              <span class="home-text07">
                <span>$</span>
                <span></span>
              </span>
              <span class="home-free-plan-price">0</span>
            </div>
            <div class="home-container09">
              <div class="home-container10">
                <span class="home-text10">✔</span>
                <span class="home-free-plan-features">
                  Access to basic token supply and price details
                </span>
              </div>
              <div class="home-container11">
                <span class="home-text11">✔</span>
                <span class="home-free-plan-features1">
                  Limited roadmap access
                </span>
              </div>
              <div class="home-container12">
                <span class="home-text12">✔</span>
                <span class="home-free-plan-features2">
                  Disclaimer section included
                </span>
              </div>
              <div class="home-container13">
                <span class="home-text13">✔</span>
                <span class="home-free-plan-features3">Free Plan Feature</span>
              </div>
            </div>
            <button class="home-button button">Continue with Free</button>
          </div>
          <div class="home-pricing-card1">
            <div class="home-container14">
              <span class="home-text14 heading3">BASIC</span>
              <span class="home-basic-plan-description">
                Upgrade to our basic plan for more features
              </span>
            </div>
            <div class="home-container15">
              <span class="home-text15">
                <span>$</span>
                <span></span>
              </span>
              <span class="home-basic-plan-pricing">7</span>
              <span class="home-text18">/ month</span>
            </div>
            <div class="home-container16">
              <div class="home-container17">
                <span class="home-text19">✔</span>
                <span class="home-text20">All features of FREE plan</span>
              </div>
              <div class="home-container18">
                <span class="home-text21">✔</span>
                <span class="home-basic-plan-features">
                  Full token supply and price details
                </span>
              </div>
              <div class="home-container19">
                <span class="home-text22">✔</span>
                <span class="home-basic-plan-features1">
                  Complete roadmap access with quarterly steps
                </span>
              </div>
              <div class="home-container20">
                <span class="home-text23">✔</span>
                <span class="home-basic-plan-features2">
                  Partners section with logos included
                </span>
              </div>
              <div class="home-container21">
                <span class="home-text24">✔</span>
                <span class="home-basic-plan-features3">
                  Disclaimer section included
                </span>
              </div>
            </div>
            <button class="home-button1 button">Try the Basic plan</button>
          </div>
          <div class="home-pricing-card2">
            <div class="home-container22">
              <span class="home-text25 heading3">
                <span>PRO</span>
                <br />
              </span>
              <span class="home-pro-plan-description">
                Unlock the full potential with our pro plan
              </span>
            </div>
            <div class="home-container23">
              <span class="home-text28">
                <span>$</span>
                <span></span>
              </span>
              <span class="home-pro-plan-pricing">20</span>
              <span class="home-text31">/ month</span>
            </div>
            <div class="home-container24">
              <div class="home-container25">
                <span class="home-text32">✔</span>
                <span class="home-text33"> All features of BASIC plan</span>
              </div>
              <div class="home-container26">
                <span class="home-text34">✔</span>
                <span class="home-pro-plan-features">
                  Advanced token supply and price details
                </span>
              </div>
              <div class="home-container27">
                <span class="home-text35">✔</span>
                <span class="home-pro-plan-features1">
                  Comprehensive roadmap access with detailed quarterly steps
                </span>
              </div>
              <div class="home-container28">
                <span class="home-text36">✔</span>
                <span class="home-pro-plan-features2">
                  Enhanced partners section with logos included
                </span>
              </div>
            </div>
            <button class="home-button2 button">Try the PRO plan</button>
          </div>
        </div>
      </div>
    </div>
    <div class="home-gallery">
      <div class="home-gallery1">
        <h1 class="home-gallery-heading heading2">Our portfolio</h1>
        <span class="home-gallery-sub-heading">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non
          volutpat turpis. Mauris luctus rutrum mi ut rhoncus. Integer in
          dignissim tortor.
          <span v-html="rawvxll"></span>
        </span>
        <div class="home-container29">
          <gallery-card3 rootClassName="rootClassName1"></gallery-card3>
          <gallery-card3
            image_src="https://images.unsplash.com/photo-1702426540518-5d27892dd2ec?crop=entropy&amp;cs=tinysrgb&amp;fit=max&amp;fm=jpg&amp;ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcwMzMxNzI2MHw&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=400"
            rootClassName="rootClassName3"
          ></gallery-card3>
          <gallery-card3
            image_src="https://images.unsplash.com/photo-1702234893452-52302797f873?crop=entropy&amp;cs=tinysrgb&amp;fit=max&amp;fm=jpg&amp;ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcwMzMxNzI2MHw&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=400"
            rootClassName="rootClassName2"
          ></gallery-card3>
          <gallery-card3
            image_src="https://images.unsplash.com/photo-1701542801052-3e66965e899a?crop=entropy&amp;cs=tinysrgb&amp;fit=max&amp;fm=jpg&amp;ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcwMzMxNzI2MHw&amp;ixlib=rb-4.0.3&amp;q=80&amp;w=400"
            rootClassName="rootClassName7"
          ></gallery-card3>
        </div>
      </div>
    </div>
    <div class="home-banner">
      <div class="home-banner1">
        <h1 class="home-banner-heading heading2">
          Token Supply and Price Details
        </h1>
        <span class="home-banner-sub-heading">
          Learn about our token supply and current price
        </span>
        <button class="home-banner-button button">View Details</button>
      </div>
    </div>
    <div class="home-faq">
      <div class="home-faq-container">
        <div class="home-faq1">
          <div class="home-container30">
            <span class="home-text37 sectionTitle">
              <span>FAQ</span>
              <br />
            </span>
            <h2 class="home-text40 heading2">Common questions</h2>
            <span class="home-text41">
              <span>Here are some of the most common questions that we get.</span>
              <br />
              <span>
                <span>
                  <span><span v-html="rawkwp4"></span></span>
                  <span><span v-html="rawyn77"></span></span>
                </span>
                <span>
                  <span><span v-html="rawqw1i"></span></span>
                  <span><span v-html="rawurs8"></span></span>
                </span>
              </span>
              <span>
                <span>
                  <span><span v-html="raw3i6i"></span></span>
                  <span><span v-html="rawhxsh"></span></span>
                </span>
                <span>
                  <span><span v-html="rawyogr"></span></span>
                  <span><span v-html="rawl7xi"></span></span>
                </span>
              </span>
            </span>
          </div>
          <div class="home-container31">
            <app-question
              Answer="The total token supply is XXXX tokens."
              Question="What is the total token supply?"
            ></app-question>
            <app-question
              Answer="The current price of the token is XXXX."
              Question="What is the current price of the token?"
            ></app-question>
            <app-question
              Answer="The steps planned for the first quarter are XXXX."
              Question="What are the steps planned for the first quarter?"
            ></app-question>
            <app-question
              Answer="Our partners include XXXX, XXXX, and XXXX."
              Question="Who are the partners of our crypto currency?"
            ></app-question>
            <app-question
              Answer="The disclaimer for our crypto currency is XXXX."
              Question="What is the disclaimer for our crypto currency?"
            ></app-question>
          </div>
        </div>
      </div>
    </div>
    <div class="home-footer">
      <footer class="home-footer1">
        <div class="home-container32">
          <span class="home-logo2">
            DogeXGrok
            <span v-html="rawz8q8"></span>
          </span>
          <nav class="home-nav1">
            <span class="home-nav12">Token Supply</span>
            <span class="home-nav22">Roadmap</span>
            <span class="home-nav32">Partners</span>
            <span class="home-nav42">Disclaimer</span>
            <span class="home-nav52">Blog</span>
          </nav>
        </div>
        <div class="home-separator"></div>
        <div class="home-container33">
          <span class="home-text58">© 2023 myCompany, All Rights Reserved.</span>
          <div class="home-icon-group1">
            <svg viewBox="0 0 950.8571428571428 1024" class="home-icon10">
              <path
                d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
              ></path></svg
            ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon12">
              <path
                d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
              ></path></svg
            ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon14">
              <path
                d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
              ></path>
            </svg>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import FeatureCard from '../components/feature-card'
import GalleryCard3 from '../components/gallery-card3'
import AppQuestion from '../components/question'

export default {
  name: 'Home',
  components: {
    FeatureCard,
    GalleryCard3,
    AppQuestion,
  },
  data() {
    return {
      raw16sd: ' ',
      rawcoiy: ' ',
      rawvxll: ' ',
      rawkwp4: ' ',
      rawyn77: ' ',
      rawqw1i: ' ',
      rawurs8: ' ',
      raw3i6i: ' ',
      rawhxsh: ' ',
      rawyogr: ' ',
      rawl7xi: ' ',
      rawz8q8: ' ',
    }
  },
  head: {
    title: 'Able Firm Mink',
    meta: [
      {
        property: 'og:title',
        content: 'Able Firm Mink',
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
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  background-color: var(--dl-color-primary1-blue80);
}
.home-navbar-interactive {
  width: 90%;
  display: flex;
  position: sticky;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  padding-left: var(--dl-space-space-threeunits);
  border-radius: 50px;
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  justify-content: space-between;
  background-color: var(--dl-color-gray-white);
}
.home-logo {
  font-size: 2em;
  font-family: "Lato";
  font-weight: bold;
  text-transform: uppercase;
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
.home-nav1 {
  transition: 0.3s;
}
.home-nav1:hover {
  color: #3d6e70ff;
}
.home-nav2 {
  transition: 0.3s;
  margin-left: var(--dl-space-space-twounits);
}
.home-nav2:hover {
  color: #3d6e70ff;
}
.home-nav3 {
  transition: 0.3s;
  margin-left: var(--dl-space-space-twounits);
}
.home-nav3:hover {
  color: #3d6e70ff;
}
.home-nav4 {
  transition: 0.3s;
  margin-left: var(--dl-space-space-twounits);
}
.home-nav4:hover {
  color: #3d6e70ff;
}
.home-nav5 {
  transition: 0.3s;
  margin-left: var(--dl-space-space-twounits);
}
.home-nav5:hover {
  color: #3d6e70ff;
}
.home-buttons {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-login {
  border-color: var(--dl-color-primary1-blue100);
  border-width: 1px;
  margin-right: var(--dl-space-space-twounits);
  padding-left: 1.5rem;
  border-radius: 45px;
  padding-right: 1.5rem;
}
.home-register {
  color: var(--dl-color-gray-white);
  transition: 0.3s;
  font-weight: bold;
  border-color: var(--dl-color-primary1-blue100);
  padding-left: 1.5rem;
  border-radius: 45px;
  padding-right: 1.5rem;
  background-color: var(--dl-color-primary1-blue100);
}
.home-register:hover {
  border-color: rgba(41, 20, 119, 0.9);
  padding-left: 1.5rem;
  padding-right: 1.5rem;
  background-color: rgba(41, 20, 119, 0.9);
}
.home-burger-menu {
  display: none;
}
.home-icon {
  width: var(--dl-size-size-xsmall);
  cursor: pointer;
  height: var(--dl-size-size-xsmall);
}
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: absolute;
  border-radius: 50px;
  flex-direction: column;
  justify-content: space-between;
  background-color: var(--dl-color-gray-white);
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
.home-logo1 {
  font-size: 2em;
  font-weight: bold;
}
.home-close-menu {
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-icon02 {
  fill: var(--dl-color-gray-900);
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
.home-nav11 {
  color: var(--dl-color-gray-black);
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav21 {
  color: var(--dl-color-gray-black);
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav31 {
  color: var(--dl-color-gray-black);
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav41 {
  color: var(--dl-color-gray-black);
  margin-bottom: var(--dl-space-space-unit);
}
.home-nav51 {
  color: var(--dl-color-gray-black);
  margin-bottom: var(--dl-space-space-unit);
}
.home-buttons1 {
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-login1 {
  border-color: var(--dl-color-primary1-blue100);
  border-width: 1px;
  margin-right: var(--dl-space-space-twounits);
  padding-left: 1.5rem;
  border-radius: 30px;
  padding-right: 1.5rem;
}
.home-register1 {
  color: var(--dl-color-gray-white);
  transition: 0.3s;
  border-color: var(--dl-color-primary1-blue100);
  border-width: 1px;
  padding-left: 1.5rem;
  border-radius: 30px;
  padding-right: 1.5rem;
  background-color: var(--dl-color-primary1-blue100);
}
.home-register1:hover {
  border-color: #849492ff;
  background-color: #849492ff;
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
  align-items: flex-start;
  justify-content: center;
  background-color: var(--dl-color-primary1-blue80);
}
.home-hero1 {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  min-height: auto;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: center;
}
.home-container01 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-hero-heading {
  color: var(--dl-color-gray-white);
  max-width: 800px;
  text-align: center;
  font-family: "Raleway";
  line-height: 1.6;
}
.home-hero-sub-heading {
  color: var(--dl-color-gray-white);
  font-size: 18px;
  text-align: center;
  line-height: 1.6;
}
.home-btn-group {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-hero-button2 {
  color: var(--dl-color-gray-white);
  transition: 0.3s;
  font-weight: bold;
  padding-top: var(--dl-space-space-unit);
  border-color: transparent;
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: transparent;
}
.home-hero-button2:hover {
  border-color: var(--dl-color-gray-white);
}
.home-details {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-details1 {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-fourunits);
  justify-content: space-between;
}
.home-container02 {
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text {
  color: var(--dl-color-primary1-blue80);
  text-align: left;
  font-family: "Raleway";
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-details-heading {
  width: 80%;
  text-align: left;
  font-family: "Raleway";
  line-height: 1.6;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-details-sub-heading {
  color: var(--dl-color-gray-800);
  font-size: 18px;
  text-align: left;
  line-height: 1.6;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-details-image {
  width: 500px;
  height: 500px;
  display: flex;
  position: relative;
  align-items: center;
  margin-left: var(--dl-space-space-fourunits);
  border-radius: var(--dl-radius-radius-radius4);
  background-size: cover;
  justify-content: center;
  background-image: url("/external/15a2d21a-f104-4617-974f-ee52a3d787b1-500h.jpg");
  background-position: center;
}
.home-text03 {
  top: 352px;
  left: 148px;
  color: #ffffff;
  position: absolute;
  font-size: 40px;
  align-self: center;
  font-style: normal;
  font-weight: 800;
  padding-top: var(--dl-space-space-halfunit);
  border-color: var(--dl-color-gray-black);
  border-style: solid;
  border-width: 1px;
  padding-left: var(--dl-space-space-halfunit);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-halfunit);
  padding-bottom: var(--dl-space-space-halfunit);
  background-color: #ed0d0d;
}
.home-text05 {
  line-height: 23;
}
.home-features {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-features-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-secondary-grey400);
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
.home-container03 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-features-heading {
  font-family: "Raleway";
  line-height: 1.6;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-features-sub-heading {
  color: var(--dl-color-gray-800);
  font-size: 18px;
  text-align: center;
  line-height: 1.6;
}
.home-container04 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
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
.home-pricing1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  justify-content: center;
  background-color: var(--dl-color-gray-white);
}
.home-container05 {
  gap: 0;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-pricing-heading {
  font-family: "Raleway";
  line-height: 1.6;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-pricing-sub-heading {
  color: var(--dl-color-gray-800);
  font-size: 18px;
  text-align: center;
  line-height: 1.6;
}
.home-container06 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: flex-start;
  justify-content: center;
}
.home-pricing-card {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  height: auto;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: 450px;
  min-height: 450px;
  align-items: flex-start;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-twounits);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
  background-color: var(--dl-color-primary1-blue60);
}
.home-container07 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text06 {
  font-family: "Raleway";
  font-weight: bold;
  text-transform: uppercase;
}
.home-free-plan-description {
  line-height: 1.6;
}
.home-container08 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-text07 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-free-plan-price {
  font-size: 4rem;
  font-weight: 700;
}
.home-container09 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
}
.home-container10 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text10 {
  color: var(--dl-color-gray-800);
}
.home-free-plan-features {
  color: var(--dl-color-gray-800);
}
.home-container11 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text11 {
  color: var(--dl-color-gray-800);
}
.home-free-plan-features1 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container12 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text12 {
  color: var(--dl-color-gray-800);
}
.home-free-plan-features2 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container13 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text13 {
  color: var(--dl-color-gray-800);
}
.home-free-plan-features3 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-button {
  color: var(--dl-color-gray-black);
  width: 100%;
  margin-top: auto;
  transition: 0.3s;
  font-weight: 700;
  padding-top: 1rem;
  border-color: var(--dl-color-primary1-blue100);
  border-radius: 45px;
  padding-bottom: 1rem;
  background-color: transparent;
}
.home-button:hover {
  border-color: rgba(41, 20, 119, 0.9);
  background-color: rgba(217, 217, 217, 0.1);
}
.home-pricing-card1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-twounits);
  max-width: 450px;
  min-height: 450px;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
  background-color: var(--dl-color-primary1-blue60);
}
.home-container14 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text14 {
  font-family: "Raleway";
  font-weight: bold;
  text-transform: uppercase;
}
.home-basic-plan-description {
  line-height: 1.6;
}
.home-container15 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-text15 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-basic-plan-pricing {
  font-size: 4rem;
  font-weight: 700;
}
.home-text18 {
  font-size: 1.15rem;
  font-style: normal;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-container16 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-container17 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text19 {
  color: var(--dl-color-gray-800);
}
.home-text20 {
  color: var(--dl-color-gray-800);
}
.home-container18 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text21 {
  color: var(--dl-color-gray-800);
}
.home-basic-plan-features {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container19 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text22 {
  color: var(--dl-color-gray-800);
}
.home-basic-plan-features1 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container20 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text23 {
  color: var(--dl-color-gray-800);
}
.home-basic-plan-features2 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container21 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text24 {
  color: var(--dl-color-gray-800);
}
.home-basic-plan-features3 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-button1 {
  color: var(--dl-color-gray-white);
  width: 100%;
  margin-top: auto;
  transition: 0.3s;
  font-weight: 700;
  padding-top: 1rem;
  border-color: rgba(41, 20, 119, 0.9);
  border-width: 0px;
  border-radius: 45px;
  padding-bottom: 1rem;
  background-color: var(--dl-color-primary1-blue100);
}
.home-button1:hover {
  border-color: rgba(41, 20, 119, 0.9);
  background-color: rgba(41, 20, 119, 0.9);
}
.home-pricing-card2 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: 450px;
  min-height: 450px;
  align-items: flex-start;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-twounits);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
  background-color: var(--dl-color-primary1-blue60);
}
.home-container22 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text25 {
  font-family: "Raleway";
  font-weight: bold;
  text-transform: uppercase;
}
.home-pro-plan-description {
  line-height: 1.6;
}
.home-container23 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.home-text28 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-pro-plan-pricing {
  font-size: 4rem;
  font-weight: 700;
}
.home-text31 {
  font-size: 1.15rem;
  font-style: normal;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.home-container24 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
}
.home-container25 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text32 {
  color: var(--dl-color-gray-800);
}
.home-text33 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container26 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text34 {
  color: var(--dl-color-gray-800);
}
.home-pro-plan-features {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container27 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text35 {
  color: var(--dl-color-gray-800);
}
.home-pro-plan-features1 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-container28 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-text36 {
  color: var(--dl-color-gray-800);
}
.home-pro-plan-features2 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
.home-button2 {
  color: var(--dl-color-gray-white);
  width: 100%;
  margin-top: auto;
  transition: 0.3s;
  font-weight: 700;
  padding-top: 1rem;
  border-color: #3d6e70ff;
  border-width: 0px;
  border-radius: 45px;
  padding-bottom: 1rem;
  background-color: var(--dl-color-primary1-blue100);
}
.home-button2:hover {
  border-color: rgba(41, 20, 119, 0.9);
  background-color: rgba(41, 20, 119, 0.9);
}
.home-gallery {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-gallery1 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
}
.home-gallery-heading {
  text-align: center;
  font-family: "Raleway";
  line-height: 1.6;
}
.home-gallery-sub-heading {
  color: rgb(153, 153, 153);
  text-align: center;
  line-height: 1.6;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
}
.home-container29 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-unit);
  margin-top: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr 1fr 1fr;
}
.home-banner {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: var(--dl-color-gray-black);
}
.home-banner1 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: var(--dl-size-size-maxwidth);
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: flex-start;
}
.home-banner-heading {
  color: var(--dl-color-gray-white);
  text-align: center;
  font-family: "Raleway";
  line-height: 1.6;
}
.home-banner-sub-heading {
  color: var(--dl-color-gray-white);
  max-width: var(--dl-size-size-maxwidth);
  text-align: center;
  line-height: 1.6;
}
.home-banner-button {
  color: var(--dl-color-gray-white);
  transition: 0.3s;
  font-weight: 700;
  padding-top: 1.5rem;
  border-width: 0px;
  padding-left: 3rem;
  border-radius: 45px;
  padding-right: 3rem;
  padding-bottom: 1.5rem;
  background-color: var(--dl-color-primary1-blue100);
}
.home-banner-button:hover {
  border-color: rgba(41, 20, 119, 0.9);
  background-color: rgba(41, 20, 119, 0.9);
}
.home-faq {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-faq-container {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
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
.home-container30 {
  display: flex;
  max-width: 35%;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text37 {
  color: var(--dl-color-primary1-blue80);
  font-family: "Raleway";
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text40 {
  font-family: "Raleway";
  line-height: 1.6;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text41 {
  color: var(--dl-color-gray-800);
  font-size: 18px;
  text-align: left;
  line-height: 1.6;
}
.home-container31 {
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
  background-color: var(--dl-color-gray-black);
}
.home-footer1 {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  justify-content: space-between;
}
.home-container32 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-logo2 {
  color: var(--dl-color-gray-white);
  font-size: 2em;
  font-weight: bold;
}
.home-nav1 {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
}
.home-nav12 {
  color: var(--dl-color-secondary-gray500);
  margin-left: 0px;
}
.home-nav22 {
  color: var(--dl-color-secondary-gray500);
  margin-left: var(--dl-space-space-unit);
}
.home-nav32 {
  color: var(--dl-color-secondary-gray500);
  margin-left: var(--dl-space-space-unit);
}
.home-nav42 {
  color: var(--dl-color-secondary-gray500);
  margin-left: var(--dl-space-space-unit);
}
.home-nav52 {
  color: var(--dl-color-secondary-gray500);
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
  border-color: var(--dl-color-gray-800);
  border-style: solid;
  border-width: 1px;
  margin-right: 0px;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
}
.home-container33 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-text58 {
  color: var(--dl-color-secondary-gray500);
}
.home-icon-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-icon10 {
  fill: var(--dl-color-secondary-gray500);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
}
.home-icon12 {
  fill: var(--dl-color-secondary-gray500);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
}
.home-icon14 {
  fill: var(--dl-color-secondary-gray500);
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
  .home-details-sub-heading {
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
  .home-container06 {
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
  .home-gallery-sub-heading {
    text-align: center;
  }
  .home-container29 {
    grid-template-columns: 1fr 1fr 1fr;
  }
  .home-banner-sub-heading {
    max-width: 100%;
  }
  .home-text41 {
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
  .home-mobile-menu {
    padding-top: var(--dl-space-space-oneandhalfunits);
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-nav11 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav21 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav31 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav41 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-nav51 {
    margin-left: 0;
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
  .home-details1 {
    align-items: center;
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
    flex-direction: column;
    justify-content: center;
  }
  .home-container02 {
    align-items: center;
    justify-content: flex-start;
  }
  .home-text {
    text-align: center;
  }
  .home-details-heading {
    text-align: center;
  }
  .home-details-sub-heading {
    text-align: center;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-details-image {
    margin-top: var(--dl-space-space-threeunits);
    margin-left: 0px;
  }
  .home-features1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-features-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-container04 {
    grid-template-columns: 1fr;
  }
  .home-pricing1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-pricing-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-container06 {
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
  .home-gallery1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-gallery-sub-heading {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-container29 {
    grid-template-columns: 1fr 1fr;
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
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
    flex-direction: column;
  }
  .home-container30 {
    max-width: 100%;
    align-self: center;
    align-items: center;
    justify-content: center;
  }
  .home-text41 {
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
  .home-container33 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .home-text58 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .home-navbar-interactive {
    width: 90%;
    padding: var(--dl-space-space-unit);
  }
  .home-logo {
    font-size: 1.5em;
  }
  .home-mobile-menu {
    padding: 16px;
  }
  .home-logo1 {
    font-size: 1.5em;
  }
  .home-icon02 {
    fill: var(--dl-color-gray-900);
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
  .home-btn-group {
    flex-direction: column;
  }
  .home-hero-button2 {
    margin-top: var(--dl-space-space-unit);
    margin-left: 0px;
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
  .home-gallery1 {
    padding: var(--dl-space-space-unit);
  }
  .home-container29 {
    grid-template-columns: 1fr;
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
  .home-container33 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .home-text58 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
