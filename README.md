# first-repo
Lets start


<!DOCTYPE html>
<html lang="en">
    <!-- npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="output.css">
    <style>
   
    @keyframes zigzagMovement {
      0% {
        transform: translate(0, 0); 
      }
      25% {
        transform: translate(-15px, 0); 
      50%} {
        transform: translate(-15px, -5px);
      }
      75% {
        transform: translate(0, -15px); 
      }
      100% {
        transform: translate(0, 0); 
      }
    }
    

    /* Apply the animation to the image */
    .animate-zigzag {
      animation: zigzagMovement 5s ease-in-out infinite;
    }
  </style>
  <style>
     @keyframes moveLeftRight {
        0% {
            transform: translateX(0); /* Start position */
        }
        25% {
            transform: translateX(-20px); /* Move left */
        }
        50% {
            transform: translateX(20px); /* Move right */
        }
        75% {
            transform: translateX(-20px); /* Move left */
        }
        100% {
            transform: translateX(0); /* End position smoothly */
        }
    }
        .animate-left-right {
            animation: moveLeftRight 5s ease-in infinite;
        }</style>
</head>
<body class="bg-cyan-500">
  <main class="bg-cyan-500   dark:bg-indigo-950 scroll-smooth text-sm"> 
    <header class="sticky top-0 z-50 text-sm">
        <h1 class="display:inline font-bold text-5xl text-center rounded-bl-lg dark:text- 
         text-purple-700 border-2 border-orange-600
         bg-gray-300">ANKUR'S PROFILE</h1>
        
        <!-- navigation bar -->
        <nav class="flex flex-row  justify-between items-center bg-blue-300 m-1 p-0 text-sm">  
           <section><button class="font-semibold rounded-full px-2 py-2 bg-gray-300 hover:bg-gray-200">
            Nightmode</button></section> 

           <section class=" flex space-x-4">
            <section class="font-bold border-4 border-red-600 shadow-gray-800 m-2 p-1.5">
                <a href="#home" class="hover:bg-orange-400 p-1">Home</a></section>
            <section class="font-bold border-4 border-red-600 m-2 p-1.5">
                <a href="#about us" class="hover:bg-orange-400 p-1">About</a></section>
            <section class="font-bold border-4 border-red-600 m-2 p-1.5">
                <a href="#skills" class="hover:bg-orange-400 p-1">Skills</a></section>
            <section class="font-bold border-4 border-red-600 m-2 p-1.5">
                <a href="#Certificate" class="hover:bg-orange-400 p-1">Services</a></section>
            <section class="font-bold border-4 border-red-600 m-2 p-1.5">
                <a href="#contact" class="hover:bg-orange-400 p-1">Contact</a></section>
        </section>
            </nav>
             </header>
    <br>
    <br>
     <!--Home-->
    <section id="home" class="h-screen w-screen flex flex-row justify-between items-center text-sm  border-b-gray-500 bg-blue-300">
        <article class="border-2 border-red-700 h-70 w-150">
            <h3 class="font-bold text-shadow-1g/80 ml-40 text-3xl">
                Known to world as</h3><br>
            <h2 class="space-x-3 ml-50 text-2xl border-4 font-semibold italic text mr-45 p-5
             animate-pulse duration-1000"> Mr.Ankur Singh</h2><br>
            <p class="ml-20 text-xl font-bold">I am an MBA and in pursuit of FSD Developer</p>
            <br>
           
            <a href="./images/Ankur CV.pdf"download class="group inline-flex items-center gap-2 px-3 py-2 ml-60 p-2
             bg-yellow-400 text-fuchsia-800 font-medium rounded-md hover:bg-emerald-700 transition duration-300"
>
        <svg class="w-5 h-5 animate-pulse group-hover:animate-bounce"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 16v2a2 2 0 002 2h12a2 2 0 002-2v-2M7 10l5 5m0 0l5-5m-5 5V4" />
        </svg>
        <span>My CV</span>
</a>
        </article>
<!-- About us -->
         <article class="w-120 h-120 mr-10 "><img src ='./images/My image.jpg' alt='Ankur Singh' 
            class="rounded-full border-2 ring-2 ring-yellow-300 animate-zigzag">
        </article> 
    </section><br/>

        <section id="about us" class="h-screen w-screen flex flex-col items-start justify-center pl-10px">
  
            <div class="flex items-center justify-start space-x-4 md:text-center">
                <div class="flex flex-col">
                  <h2 class="ml-10 text-4xl font-extrabold text-amber-100 animate-bounce";
             animation-timing-function: ease-out;>ABOUT US</h2>
                    <h2 class="font-bold italic ml-10 text-2xl text-fuchsia-500">MBA Finance Turning to FSD</h2>
                    
                <p class="max-w-lg ml-5 text-xl text-blue-300 md:text-center">MBA in Finance with over 8 years of experience in accounting,
                     capital budgeting, and risk management within the brokerage industry. 
                     Proven track record as a Senior Team Leader, responsible for overseeing end-of-day (EOD) risk management
                      processes to ensure accuracy, timeliness, and compliance. 
                      Possess strong analytical skills and a deep understanding of 
                      financial controls and operational risk frameworks. </p>
                    </div>
                    <img src="./images/Myimage 2.jpg " alt="about me image"class="w-1/3 ml-auto h-auto mr-30
                     rounded-lg animate-left-right">
                </div>
            
         </section>
         <!-- Skills -->
         <section id="skills" class="h-screen w-screen flex flex-col justify-start items-center">
 <div class="mt-48">
    <h2 class="text-4xl text-center text-orange-400">MY Proficient and Developing Skills</h2>
            
    <div class="group"> 
      <div class="flex justify-between mb-1 w-3xl">
      <span class=" font-bold text-amber-200 text-2xl ">HTML</span>
      <span class="text-2xl font-bold italic  text-amber-400">80%</span>
    </div>
    <div class="w-3xl bg-gray-200 rounded-full h-4 overflow-hidden">
      <div class="bg-blue-600 h-4 rounded-full transition-all duration-700 ease-out group-hover:w-[80%] w-0"></div>
    </div></div>
             
  

      <!-- Skill -->
   <div class="group">
    <div class="flex w-3xl justify-between mb-1">
      <span class="font-bold text-amber-200 text-2xl">CSS</span>
      <span class="text-2xl font-bold italic  text-amber-400">70%</span>
    </div>
    <div class="w-3xl bg-gray-200 rounded-full h-4 overflow-hidden">
    <div class="h-4 rounded-full bg-green-600 transition-all duration-700 ease-out group-hover:w-[70%] w-0"></div>
    </div>
   </div>
 <!-- Skill -->
   <div class="group">
    <div class="flex w-3xl justify-between mb-1">
      <span class="font-bold text-amber-200 text-2xl">Ms Excel</span>
      <span class="text-2xl font-bold italic  text-amber-400">90%</span>
    </div>
    <div class="w-3xl bg-gray-200 rounded-full h-4 overflow-hidden">
      <div class="bg-red-600 h-4 rounded-full transition-all duration-700 ease-out w-0 group-hover:w-[90%] "></div>
       </div>
      </div>
     <!-- Skill -->
    <div class="group">
      <div class="flex w-3xl justify-between mb-1">
      <span class="font-bold text-amber-200 text-2xl">SQL(postgresql)</span>
      <span class="text-2xl font-bold italic  text-amber-400">75%</span>
    </div>
    <div class="w-3xl bg-gray-200 rounded-full h-4 overflow-hidden">
      <div class="bg-pink-600 h-4 rounded-full transition-all duration-700 ease-out w-0 group-hover:w-[75%]" ></div>
      </div>
    </div>
     <!-- Skill -->
<div class="group"> 
  <div class="flex w-3xl justify-between mb-1">
      <span class="font-bold text-amber-200 text-2xl">Adobe Photoshop</span>
      <span class="text-2xl font-bold italic  text-amber-400">90%</span>
    </div>
    <div class="w-3xl bg-gray-200 rounded-full h-4 overflow-hidden">
      <div class="bg-yellow-500 h-4 rounded-full transition-all duration-700 ease-out w-0 group-hover:w-[90%]" ></div>
      
    </div>
  </div>
   <!-- Skill -->
   <div class="group">
    <div class="flex w-3xl justify-between mb-1">
      <span class="font-bold text-amber-200 text-2xl">Ms Office</span>
      <span class="text-2xl font-bold italic  text-amber-400">80%</span>
    </div>
    <div class="w-3xl bg-gray-200 rounded-full h-4 overflow-hidden">
      <div class="bg-orange-600 h-4 rounded-full transition-all duraton-700 ease-out w-0 group-hover:w-[80%]"></div>
      
    </div></div>

    </div>          
      </section>
        <!-- services  -->
      <section id="Certificate" class="h-screen w-screen flex flex-col ">
      
          <h2 class="font-bold text-4xl text-cyan-200 ml-7 mt-32">Certifications</h2><br/>
       <div class="flex justify-between gap-5 flex-wrap h-5 my-18"><div class="bg-green-400 rounded-xl shadow-md overflow-hidden hover:shadow-xl 
        transition-shadow duration-300 ml-10">
    <img src="./images/NISM VIII image.png" alt="NISM 8 Certificate" class="w-full h-40 object-cover">
    <div class="p-4">
      <h3 class="text-lg font-semibold text-gray-800">NISM VIII (Equity Derivatives)</h3>
      <p class="text-sm text-gray-600">Issued by:NISM</p>
      <p class="text-sm text-gray-600">Date: Jan 2024</p>
      <a href="./images/NISM VIII.pdf" target="_blank"
         class="text-blue-600 hover:underline mt-2 inline-block text-sm font-medium">
        View Certificate
      </a>
    </div>
  </div>
  
  <div class="bg-green-400 rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow duration-300 gap-5">
    <img src="./images/NISM XVI image.png" alt="NISM 16 Certificate" class="w-full h-40 object-cover">
    <div class="p-4">
      <h3 class="text-lg font-semibold text-gray-800">NISM XVI (Commodity Derivatives)</h3>
      <p class="text-sm text-gray-600">Issued by:NISM</p>
      <p class="text-sm text-gray-600">Date: Jan 2024</p>
      <a href="./images/NISM XVI(Commodity Derivatives).pdf" target="_blank"
         class="text-blue-600 hover:underline mt-2 inline-block text-sm font-medium">
        View Certificate
      </a>
    </div>
  </div>
  <div class="bg-green-400 rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow
   duration-300 gap-5 mr-10">
    <img src="./images/NISM VII image.png" alt="NISM 7 Certificate" class="w-full h-40 object-cover">
    <div class="p-4">
      <h3 class="text-lg font-semibold text-gray-800">NISM VII (Risk Management)</h3>
      <p class="text-sm text-gray-600">Issued by:NISM</p>
      <p class="text-sm text-gray-600">Date: Jan 2024</p>
      <a href="./images/NISM VII (Risk Management).pdf" target="_blank"
         class="text-blue-600 hover:underline mt-2 inline-block text-sm font-medium ">
        View Certificate
      </a>
    </div>
  </div></div>   
         </section>
        <!-- Projects -->
         <section id="projects" class="h-screen w-screen">
          <h2 class="font-bold italic text-3xl text-purple-400">Past and Upcoming Projects</h2><br/>
          <div class="flex flex-wrap justify-evenly max-w-6xl mx-auto gap-4">
            <div class="w-60 bg-orange-600 rounded-3xl p-3 font-extrabold text-green-300 break-words">Project Title: Risk Management
               Framework Development Aligned with Regulatory Requirements

I led a project aimed at developing a comprehensive Risk Management framework aligned with regulatory
 mandates from SEBI and internal compliance policies. The objective was to streamline risk identification, 
 control mechanisms, and reporting across the trading and back-office systems.

My role involved interpreting key regulatory requirements such as margin norms, 
exposure limits, and position monitoring, and converting them into actionable risk rules.
I also worked with QA to design test cases for regulatory scenarios and ensured
 proper audit trail and exception logging.</div>
            <div class="w-60 bg-orange-600 rounded-3xl p-3 font-extrabold text-green-300 break-words">roject Title: Real-Time
               Risk Management Adjustment During Ukraine Crisis – Commodities Segment

During the initial stages of the Russia-Ukraine conflict,
 I played a key role in enhancing the risk management framework for commodity trades in
  response to increased market volatility and regulatory alerts. My responsibility was to reassess
   margin models, integrate higher exposure buffers, and ensure timely implementation with the IT development team.

Key contributions:

Monitored extreme price fluctuations in key commodities (e.g., crude oil, metals) and recommended higher
 initial and exposure margins.

Collaborated with the IT team to integrate new risk thresholds
 and real-time circuit breakers into the trading system.

Worked with compliance to ensure margin hikes adhered to SEBI/Exchange circulars and internal risk guidelines.</div>
            <div class="w-60 bg-orange-600 rounded-3xl p-3 font-extrabold text-green-300 break-words">UPCOMING PROJECT</div>
            <div class="w-60 bg-orange-600 rounded-3xl p-3 font-extrabold text-green-300 break-words">UPCOMING PROJECT</div>
            


          </div><br/>
          <!-- Contact -->
           <div id="contact" class="w-screen h-screen">
            <h3 class="text-4xl font-extrabold bg-white text-blue-700 text-center mt-24">Contact Me</h3>
            
            <form class=space-y-4>
              <div class="ml-20 mr-20">
      <label for="name" class="block text-xl font-medium text-orange-200">Name</label>
      <input type="text" id="name" name="name" placeholder="Your name "
             class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm
              text-orange-200 focus:outline-none focus:ring-2 focus:ring-blue-400" />
    </div>

    <!-- Email -->
    <div class="ml-20 mr-20">
      <label for="email" class="block text-sm font-medium text-orange-200">Email</label>
      <input type="email" id="email" name="email" placeholder="you@example.com"
             class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm text-orange-200
              focus:outline-none focus:ring-2 focus:ring-blue-400" />
    </div>

    <!-- Message -->
    <div class="ml-20 mr-20 bg-gray-500">
      <label for="message" class="block text-sm font-medium text-orange-200">Message</label>
      <textarea id="message" name="message" rows="4" placeholder="Your message..."
                class="mt-1 block w-full px-4 py-2 border bg-gray-800 border-gray-300 text-orange-200 rounded-md 
                shadow-sm focus:outline-none focus:ring-2 focus:ring-blue-400"></textarea>
    </div>

    <!-- Submit Button -->
    <div class="ml-20 mr-20 ">
      <button type="submit"
              class="w-full bg-blue-500 text-white py-2 px-4 rounded-md hover:bg-blue-600 transition-colors">
        Send Message
      </button>
    </div>
            </form>
           </div>

         </section>
         </main><br/><br/>
         ><br/>
         ><br/>

         <!-- Footer -->
  <footer class="bg-gray-800 text-white py-4 text-center mt-96 p-96">
    <div class="flex justify-center space-x-4 bg-gray-800">
      <a href="tel:+919930821541" class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded">📞 Call</a>
      <a href="mailto:ankursingh3004@icloud.com" class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded">✉️ Email</a>
    </div>
  </footer>
   
    
</body>
</html>
