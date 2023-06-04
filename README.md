# my...

<!DOCTYPE html>
<html>
    <head> 
        <title>
            FAQ's......
        </title>
        <link rel ="stylesheet" type="text/css" href="faq.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    </head>
    <body>
        <div class="wrapper">
            <p> "Join us in creating a world with access to quality healthcare for all"</p>
            <h1> Frequently Asked Questions</h1>

            <div class="faq">
                <button class="accordian">
                    What types of medical equipment are accepted for donation?
                    <i class="fa-solid fa-chevron-down"></i>
                    </button>
                    <div class="panel">
                        <p>
                            The types of medical equipment accepted for donation
                            are typically accepted include hospital beds, wheelchairs, walkers, crutches, 
                        </p>
                    </div>
            </div>
            <div class="faq">
                <button class="accordian">
                    How can I donate my medical equipment?
                    <i class="fa-solid fa-chevron-down"></i>
                    </button>
                    <div class="panel">
                        <p>
                            You can donate your medical equipment by contacting us and 
                            also registering to our website will ensure your donation.
                        </p>
                    </div>
            </div>
            <div class="faq">
                <button class="accordian">
                    Is there a specific process I need to follow to donate my equipment?
                    <i class="fa-solid fa-chevron-down"></i>
                    </button>
                    <div class="panel">
                        <p>
                            The process for donating medical equipment is 
                            that  you will need to fill out a donation form,by registering to our website,
                             provide information about the equipment you wish
                              to donate, and arrange for pick-up or drop-off.
                        </p>
                    </div>
            </div>
            <div class="faq">
                <button class="accordian">
                    How does the donation process work?

                    <i class="fa-solid fa-chevron-down"></i>
                    </button>
                    <div class="panel">
                        <p>
                            The donation process typically involves contacting the organization 
                            or program, filling out a donation form, providing information about
                             the equipment, and arranging for pick-up or drop-off. The equipment is
                              then processed, cleaned, and distributed to  individuals in need.
                        </p>
                    </div>
            </div>
            <div class="faq">
                <button class="accordian">
                    What happens to the equipment after it is donated?

                    <i class="fa-solid fa-chevron-down"></i>
                    </button>
                    <div class="panel">
                        <p>
                            After the equipment is donated, it is typically cleaned, refurbished,
                             and repaired (if necessary) before being distributed to healthcare facilities,
                              clinics, or individuals in need.
                            
                        </p>
                    </div>
            </div>
            <div class="faq">
                <button class="accordian">
                    Do you accept used medical equipment, or does it have to be new?
                    <i class="fa-solid fa-chevron-down"></i>
                    </button>
                    <div class="panel">
                        <p>
                            Most medical equipment donated is both used and new so we accept both. 
                        </p>
                    </div>
            </div>
            <div class="faq">
                <button class="accordian">
                    How can I ensure that my donated equipment will be put to good use?
                    <i class="fa-solid fa-chevron-down"></i>
                    </button>
                    <div class="panel">
                        <p>
                            To ensure that your donated equipment is put to good use,
                            You can  ask for information about how the equipment
                             will be distributed and used, and request updates or feedback
                              about the impact of your donation.
                        </p>
                    </div>
            </div>
            <script>
                var acc=document.getElementsByClassName("accordian");
                var i;
                
                for(i=0;i<acc.length;i++)
                {
                  acc[i].addEventListener("click",function(){
                      this.classList.toggle("active");
                      this.parentElement.classList.toggle("active");
      
                       var panel=this.nextElementSibling;
                       if(panel.style.display=="block")
                       {
                          panel.style.display="none";
                       }else{
                          panel.style.display="block";
                       }
                  });
                }
              </script> 
              </div>
    </body>
</html>
