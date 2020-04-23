<template>
  <div class="resume-body">
    <div class="resume-card">
      <div class="resume-header">
        <div class="level">
          <div class="level-left is-flex">
            <div class="resume-header-logo">PB</div>
            <div class="resume-header-name">
              Prajwal Bharadwaj
            </div>
          </div>
          <div class="level-right resume-header-links is-flex is-vcenter">
            <div class="level-item has-text-centered">About Me</div>
            <div class="level-item has-text-centered">Resume</div>
            <div class="level-item has-text-centered">Portfolio</div>
          </div>
        </div>
      </div>

      <div class="resume-content"></div>

      <div class="resume-content">
        <div class="resume-section">
          <div class="resume-section-title">Description</div>
          <div class="resume-section-content ">
            <p>
              <strong>Creative Front End Developer</strong> with
              <strong>2.5 years of experience</strong> in
              <strong
                >designing, developing and managing complex web
                applications</strong
              >
              by using <strong>open source libraries</strong> and frameworks.
              Specialized in
              <strong
                >admin application, responsive design, improve UI and UX</strong
              >
              using
              <strong>Vue.js, Vuetify and Bootstrap.</strong>
            </p>
          </div>
        </div>

        <div class="resume-section">
          <div class="resume-section-title">Experience</div>
          <div class="resume-section-content ">














              

<div class="timeline">
	
	<div class="timeline-item" >
    <div class="timeline-title">
      <div class="timeline-title-year">March 2020 - Present</div>
    </div>
    <div class="timeline-content">
      <div class="timeline-content-subtitle">SenseHawk India</div>
      <div class="timeline-content-title">
        Front End Software Developer
      </div>
      <div class="timeline-content-desc">
        Currently Working
      </div>
    </div>
	</div>



  <div class="timeline-item" >
    <div class="timeline-title">
      <div class="timeline-title-year">March 2019 - March 2020</div>
      
    </div>
    <div class="timeline-content">
      <div class="timeline-content-subtitle">Avi Solar / EnerMAN Technologies Pvt Ltd, Bangalore</div>
      <div class="timeline-content-title">
        UI/UX Designer and Developer
      </div>
      <div class="timeline-content-desc">
        <p>
          Revamped UI of the Web interface for customers who monitor the SOLAR Power plant which was using tables into
          more interactive by using graph and the material card.
        </p>
        <p>
          Gathered requirements for two of the major products and converted into User Experience Design and developed the interface from scratch which increased the customer satisfaction by 40% to monitor Solar plants.
        </p>
        <p>
          Designing and developing wireframes/mockups into responsive, single page application, progressive web app and interactive features using Vue.js and Vuetify with additional open source libraries for graph and other components used in analytics.
        </p>
        <p>
          Introduced wireframing tools such as Figma, Illustrator and Adobe XD, and Information Architecture concept to increase team productivity.
        </p>
      </div>
    </div>
	</div>






  <div class="timeline-item" >
    <div class="timeline-title">
      <div class="timeline-title-year">April 2017 - November 2018</div>
      
    </div>
    <div class="timeline-content">
      <div class="timeline-content-subtitle">Spin Technologies Pvt Ltd, Bangalore</div>
      <div class="timeline-content-title">
        Front End Developer
      </div>
      <div class="timeline-content-desc">
        
        <p>Understanding the customer requirements and creating the wireframes/mockups  and prototype with customization or enhancement required.</p>
        <p>Handling various technical aspects of an application with maintenance and support.</p>
        <p>Collaborate with the client’s teams in collecting and understanding the requirements and customizations required in the process of creating and testing the design. </p>
        <p>Ensuring that the design requirements and specifications for the modules which are coded by me are tested and fulfilled before the code is delivered.</p>
      </div>
    </div>
	</div>



  
	
  


	
</div>










          </div>
        </div>





      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import "@/assets/lib/style/core/main/resume.scss";
.navbar-name {
  font-size: 20px;
  margin-right: 20px;
}

.resume-body {
  background-color: $blue-primary;
  min-height: 100vh;
}

.resume-card {
  color: #fff;
  background-color: $bg-dark;
  margin: 40px 60px;
  min-height: 100vh;
  border-radius: 50px;
}
.resume-header {
  padding: 40px;
  border-bottom: 2px solid $border-dark;

  &-logo {
    font-size: 28px;
    margin-right: 20px;
    background-color: $blue-primary;
    height: 56px;
    width: 56px;
    border-radius: 50%;
    text-align: center;
    line-height: 56px;
    font-weight: bold;
  }
  &-name {
    font-size: 24px;
  }

  &-links {
    color: rgba(245, 245, 245, 0.55);
    div {
      padding: 0 30px;
    }
  }
}

.resume-content {
  .resume-section {
    padding: 40px;

    &-title {
      font-weight: 600;
      display: inline-block;
      position: relative;
      font-size: 21px;
      margin: 0 0 30px;
      z-index: 1;
      padding-bottom: 7px;

      &::before {
        display: block;
        position: absolute;
        content: "";
        width: 100%;
        background-color: #353535;
        height: 2px;
        bottom: 0;
      }

      &::after {
        display: block;
        position: absolute;
        content: "";
        width: 30px;
        background-color: #007ced;
        height: 2px;
        bottom: 0;
      }
    }

    &-content {
      &>p {
        color: #d5d5d5;
        font-size: 14px;
        max-width: 70%;
        strong {
          color: #f5f5f5;
          font-weight: 800;
        }
      }
    }
  }
}

.is-dark-navbar {
  color: $white;
  background-color: $bg-dark;
}














.timeline {
	max-width: 1024px;
	width: 90%;
	margin: 0 auto;
}

// ----------------  THE FONTS

$border-color: rgba(white, .3);

.timeline-item {
	padding: 1.0em 2em 2em;
	position: relative;
	color: rgba(white, .7);
  border-left: 2px solid $border-color;
  
  .timeline-title {
    display: flex;
    align-items: center;
    &-year{
      font-size: 14px;
      display: inline-block;
      color: #d5d5d5;
      font-weight: 600;
      border: 2px solid $blue-primary;
      padding: 0px 10px;
      line-height: 25px;
      border-radius: 30px;
      background-color: #000;
      position: relative;
      left: -50px;
    }



  }

  .timeline-content {
    padding: 15px 0 15px 30px;

    &-title{
      color: #f5f5f5;
      font-size: 18px;
      font-weight: 600;
    }
    &-subtitle{
      color: #aaaaaa;
    }
  }
	
	// p {
	// 	font-size: 1rem;
	// }
	
	// &::before {
	// 	content: '';
	// 	position: absolute;
	// 	left: 2em;
	// 	font-weight: bold;
	// 	top: 1em;
	// 	display: none;
	// 	font-family: 'Roboto', sans-serif;
	// 	font-weight: 700;
	// 	font-size: .785rem;
	// }

	// &::after {
	// 	width: 10px;
	// 	height: 10px;
	// 	display: none;
	// 	top: 1em;
	// 	position: absolute;
	// 	left: -6px;
	// 	border-radius: 10px;
	// 	content: '';
	// 	border: 2px solid $border-color;
	// 	background: white;
	// }

	&:last-child {
		border-image: linear-gradient(
			to bottom,
			$border-color 60%,
			rgba($border-color, 0)) 1 100%
		;
	}
}











@media screen and (max-width: 768px) {
  
  

  .timeline {
	max-width: 1024px;
	width: 100%;
	margin: 0 auto;
}

// ----------------  THE FONTS

$border-color: rgba(white, .3);

.timeline-item {
	padding: 1.0em 2em 2em;
	position: relative;
	color: rgba(white, .7);
  border-left: 2px solid $border-color;
  
  .timeline-title {
    display: flex;
    &-year{
      font-size: 14px;
    display: inline-block;
    color: #d5d5d5;
    font-weight: 600;
    border: 2px solid $blue-primary;
    padding: 0px 10px;
    line-height: 25px;
    border-radius: 30px;
    background-color: #000;
    position: relative;
    left: -50px;
    }
  }

  .timeline-content {
    padding: 20px 0;
  }

	&:last-child {
		border-image: linear-gradient(
			to bottom,
			$border-color 60%,
			rgba($border-color, 0)) 1 100%
		;
	}
}









  .resume-card {
    color: #fff;
    background-color: $bg-dark;
    margin: 20px;
    min-height: 100vh;
    border-radius: 25px;
  }

  .resume-header-links {
    display: flex;
    justify-content: center;
    div {
      padding: 10px !important;
      &.level-item:not(:last-child) {
        margin: 0;
        padding: 0;
        justify-content: center;
      }
    }
  }

  .resume-content {
    .resume-section {
      padding: 40px;

      &-title {
        font-weight: 600;
        display: inline-block;
        position: relative;
        font-size: 21px;
        margin: 0 0 30px;
        z-index: 1;
        padding-bottom: 7px;

        &::before {
          display: block;
          position: absolute;
          content: "";
          width: 100%;
          background-color: #353535;
          height: 2px;
          bottom: 0;
        }

        &::after {
          display: block;
          position: absolute;
          content: "";
          width: 30px;
          background-color: #007ced;
          height: 2px;
          bottom: 0;
        }
      }

      &-content {
        p {
          color: #d5d5d5;
          font-size: 14px;
          max-width: 100%;
          strong {
            color: #f5f5f5;
            font-weight: 800;
          }
        }
      }
    }
  }
}
@media screen and (min-width: 769px) {
}
@media screen and (min-width: 1024px) {
}
@media screen and (min-width: 1216px) {
}
</style>
