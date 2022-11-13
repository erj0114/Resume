<template>
  <div id="app">
    <!-- Left Side START -->
    <div id="left-side">
      <h1>Eric Johnson</h1>
      
      <h4><div class="profession">Web Developer</div></h4>
      <hr />
      <h2><div class="contact">Contact</div></h2>
      <hr />
      <div>Address</div>
      <div>Chicago, IL</div>
      <br />
      <div>Phone</div>
      <div>‪(312) 857-3866‬</div>
      <br />
      <div>E-mail</div>
      <div>Eric@IMEJTech.com</div>

      <hr />
      <h2><div class="skills">Skills</div></h2>
      <hr />
      
      <div>Content marketing strategy</div>
      <br />
      <div>Web user interfaces</div>
      <br />
      <div>Website optimization</div>
      <br />
      <div>Operating systems</div>
      <br />
      <div>Programming</div>

<hr />
      <h2>Education</h2>
      <hr />
      <h4><div class="education">Cerro Coso Community College</div></h4>
      <div> Associate of Science</div>
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
        <template v-slot:date>
          2018-Current
        </template>
        <template v-slot:position>
          Web Developer
        </template>
        <template v-slot:companyAndLocation>
          IMEJ Tech, Chicago IL
        </template>
        <template v-slot:experience>
          <ul>
            <li>
              Used various technologies, including VUE and Bootstrap to build
              and make code repairs to optimize corporate websites.
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

      <work-history>
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
      </work-history>

      <work-history>
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
      </work-history>

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
      </work-history>
    </div>
    <!-- Left Side END -->
  </div>
</template>

<script>
import WorkHistory from "./components/WorkHistory";
export default {
  name: "App",
  components: {
    WorkHistory,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;

  display: flex;
  flex-direction: row;
}

#left-side {
  min-width: 300px;
  background: rgb(44, 75, 252);
  color: white;
  padding: 10px;
}

#right-side {
  padding: 10px;
  font-size: 11pt;
}
</style>
