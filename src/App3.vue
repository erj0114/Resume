<template>
  <div id="app">
    <!-- Left Side START -->
    <div id="left-side">
      <h1>Eric Johnson</h1>
      <h4><div class="profession">Web Developer</div></h4>
      <br />
      <hr />
      <h2><div class="contact">Contact</div></h2>
      <hr />
      <!-- <div>Address:</div> -->
      <!-- <div>Chicago, IL</div> -->
      <!-- <div>Phone:</div>
      <a href="tel:+1-708-217-4916">‪(708) 217-4916‬</a><br />
      <br /> -->
      
      <div>E-mail:</div>
      <a href="mailto:Eric@ImejTech.com">
        <i class="far fa-envelope"></i>Eric@ImejTech.com
      </a>
      or
      <br />
      <a href="mailto:Erj0114@Att.net">
        <i class="far fa-envelope"></i>Erj0114@att.net
      </a>
      <br /><br />
      <hr />
      <h2>Education</h2>
      <hr />
      <!-- <a href="https://www.cerrocoso.edu/">Cerro Coso Community College</a -->
      <!-- <br /><br /> -->
      <div>
        B.S. in Computer Science, Northeastern Illinois University, 2025.
      </div>
      <br />
      <div>A.A. Behavioral Science, Cerro Coso Community College, 2017.</div>
      <br />
      <hr />
      <h2>Certifications</h2>
      <hr />
      <div>NEIU Eagle HackFest, First place, 2023.</div>
      <br />
      <div>Code Camp, View Responsive Web Design Certification, 2019.</div>
      <br />
    </div>
    <!-- Left Side END -->

    <!-- Right Side START -->
    <div id="right-side">
      <div class="summary">
        Self-motivated Web Developer with high level of experience working on
        multiple projects. Passionate and hardworking with penchant for meeting
        deadlines. Interested in role with company promoting best practices and
        offering diverse customer projects.
      </div>
      <hr />
      <h2>Recent Work History</h2>
      <hr />
      <work-history>
        <template v-slot:date> 2019-Current </template>
        <template v-slot:position> Web Developer </template>
        <template v-slot:companyAndLocation> IMEJ Tech, Chicago IL </template>
        <template v-slot:experience>
          <ul>
            <li>
              Used various technologies, including Vue.js, Bootstrap, FileZilla,
              Node.js, Photoshop, GIMP, PostgreSQL 12, and Ubuntu 18.04 LTS. To
              build and make code repairs to optimize corporate websites.
            </li>
            <li>
              Created site layout and user interface using HTML and CSS
              practices.
            </li>
            <li>
              Used programming capabilities in PHP, SQL and JavaScript and other
              libraries as needed.
            </li>
            <li>Converted mockups into HTML, JavaScript, AJAX and JSON.</li>
            <li>
              Tested websites and performed troubleshooting prior to deployment.
            </li>
            <li>
              Researched new technologies, software packages and hardware
              products for use in website projects.
            </li>
            <li>
              Designed sites to be compatible with top browsers, including
              Firefox, Chrome and Safari.
            </li>
            <li>Built Websites from Scratch, Squarespace, and WordPress.</li>
          </ul>
        </template>
      </work-history>

      <div class="summary"></div>
      <hr />
      <h2>About</h2>
      <hr />
      <work-history>
        <template v-slot:date> Started in 2018 </template>
        <template v-slot:position> Web Developer </template>
        <template v-slot:companyAndLocation>
          My journey of web development
        </template>
        <template v-slot:experience>
          <ol>
            <li>
              My introduction to Web Development was using WordPress. I got into
              web development by building a website focused on my artwork that I
              wanted to show off and sell.
            </li>
            <li>
              I took classes from code camp and learned how to build websites
              from scratch using Vue.js
            </li>
            <li>
              The next project was a website for artist to sign up and join a
              social network for artwork.
            </li>
            <li>
              I was hired on to build a website using Squarespace. It's what I
              thought would be best for the client to potentially maintain it
              himself for his smaller project.
            </li>
            <li>
              The next project was building a website for my business. I built
              the website from scratch using Vue.js to get more familar.
            </li>
            <li>
              My largest project was building a new website for my seasonal
              employer.
            </li>
            <li>
              The most current project was building a website for my resume.
            </li>
          </ol>
        </template>
      </work-history>

      <h2>Portfolio</h2>
      <hr />
      <div>
        <a class="portfolio" href="http://www.AmericanEnergyConsulting.com"
          >AmericanEnergyConsulting.com</a
        ><br /><br />
      </div>
      <div>
        <a class="portfolio" href="https://chicago-artwork.com/"
          >Chicago-Artwork.com</a
        ><br /><br />
      </div>
      <div>
        <a class="portfolio" href="https://www.ChicagoRiverPaddle.com"
          >ChicagoRiverPaddle.com</a
        ><br /><br />
      </div>
      <div>
        <a class="portfolio" href="https://artist-erj.com/#/">Artist-Erj.com</a
        ><br /><br />
      </div>
      <div>
        <a class="portfolio" href="https://EricJohnsonResume.com"
          >EricJohnsonResume.com</a
        ><br /><br />
      </div>
      <div>
        <a class="portfolio" href="https://www.ImejTech.com">ImejTech.com</a
        ><br /><br />
        <hr />
      </div>

      <!-- <work-history>
        <template v-slot:date> 2019-Current</template>
        <template v-slot:position>
          Seasonal Sports Rental /Retail Sales Associate</template
        >
        <template v-slot:companyAndLocation>
          Chicago River Paddle Chicago, IL</template
        >
        <template v-slot:experience>
          <ul>
            <li>
              Improved operational efficiencies while managing customers
              requests, store inventory, transactions, new purchase orders and
              pricing needs.
            </li>
            <li>
              Balanced and organized cash register by handling cash, counting
              change and storing coupons.
            </li>
            <li>
              Maintained clean personal appearance, modeled store's outfits when
              working clothing department settings and wore uniforms per company
              policy.
            </li>
            <li>
              Supported efficient and timely replenishment of sales floor
              merchandise.
            </li>
            <li>
              Offered each customer top-notch, personal service and polite
              support to boost sales and customer satisfaction.
            </li>
            <li>
              Maintained excellent attendance record, consistently arriving to
              work on time.
            </li>
          </ul>
        </template>
      </work-history> -->

      <!-- <work-history>
        <template v-slot:date>2019-2020</template>
        <template v-slot:position> Seasonal Delivery Helper</template>
        <template v-slot:companyAndLocation>UPS Chicago, IL </template>
        <template v-slot:experience>
          <ul>
            <li>Seasonal Helper</li>
            <li>
              Used pallet jacks, handcarts and dollies to transport products to
              truck and to customers.
            </li>
            <li>
              Arranged packages on truck to achieve best use of storage space
              and to minimize damage.
            </li>
            <li>
              Secured products on truck with use of straps, load bars and
              bulkhead attachment points.
            </li>
            <li>
              Followed workplace and on-truck safety guidelines and regulations
              to prevent accidents and mishaps.
            </li>
            <li>
              Completed required product or package delivery documentation.
            </li>
            <li>
              Assisted driver with product or package deliveries to residential
              and commercial locations.
            </li>
          </ul>
        </template>
      </work-history> -->
      <!-- 
      <work-history>
        <template v-slot:date> 2017-2018</template>
        <template v-slot:position> Customer Service Associate</template>
        <template v-slot:companyAndLocation>
          Savway Fine Wines And Spirits, Oakbrook Terrace, IL</template
        >
        <template v-slot:experience
          ><ul>
            <li>
              Conferred with customers about concerns with products or services
              to resolve problems and drive sales.
            </li>
            <li>
              Maintained accurate and current customer account data with manual
              forms processing and digital information updates.
            </li>
            <li>
              Managed customer relations and customer service through daily
              communication and interaction.
            </li>
            <li>
              Evaluated customer information to explore issues, develop
              potential solutions and maintain high-quality service.
            </li>
            <li>
              Exceeded service objectives by applying proven customer service
              and sales best practices.
            </li>
            <li>
              Skilled using cash register including processing sales discounts
              and refunds.
            </li>
            <li>
              Recommended items to customers based on specific needs and
              explained features and benefits.
            </li>
            <li>
              Maintained clean personal appearance, modeled store's outfits when
              working clothing department settings and wore uniforms per company
              policy.
            </li>
          </ul>
        </template>
      </work-history> -->
    </div>
    <!-- Left Side END -->
  </div>
</template>

<script>
import WorkHistory from "./components/WorkHistory";
export default {
  name: "App2",
  components: {
    WorkHistory,
  },
};
</script>

<style>
h1,
h2,
h4 {
  margin: 5px;
}
.portfolio {
  color: black;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 10px;
  display: flex;
  flex-direction: row;
}
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
#left-side {
  min-width: 120px;
  background: rgb(49, 60, 124);
  color: white;
  padding: 10px;
}
a {
  color: white;
}
a:hover {
  color: rgb(0, 252, 252);
}

#right-side {
  padding: 10px;
  font-size: 11pt;
}

@media only screen and (max-width: 768px) {
  #app {
    flex-direction: column;
    margin-top: 0px;
    display: flex;
  }
}
@media print {
  #app {
    margin-top: 0px;
    font-size: 12pt;
  }
  #left-side {
    color: black;
    background: white;
  }
  a {
    color: black;
  }
}
</style>
