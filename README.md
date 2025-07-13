# Awan-lithotripsy-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awan Kidney Center Lithotripsy</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <style>
        .medical-gradient {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
        }
        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.05);
        }
        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 1000;
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        .section-fade {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }
        .section-fade.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- Header -->
    <header class="medical-gradient text-white shadow-lg">
        <div class="container mx-auto px-4 py-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="text-center md:text-left mb-4 md:mb-0">
                    <h1 class="text-3xl md:text-4xl font-bold mb-2">
                        <i class="fas fa-hospital-symbol mr-3"></i>
                        Awan Kidney Center Lithotripsy
                    </h1>
                    <p class="text-blue-100 text-lg">Advanced Kidney Stone Treatment Center</p>
                </div>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="https://wa.me/+923339451288" target="_blank" 
                       class="bg-green-500 hover:bg-green-600 text-white px-6 py-3 rounded-lg font-semibold transition-colors duration-300 flex items-center">
                        <i class="fab fa-whatsapp mr-2 text-xl"></i>
                        Contact Us
                    </a>
                    <a href="#services" 
                       class="bg-white bg-opacity-20 hover:bg-opacity-30 text-white px-6 py-3 rounded-lg font-semibold transition-colors duration-300 flex items-center">
                        <i class="fas fa-info-circle mr-2"></i>
                        Learn More
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-white py-16">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Non-Invasive Kidney Stone Treatment</h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                    Experience advanced lithotripsy treatment at Awan Kidney Center. Our state-of-the-art technology 
                    breaks down kidney stones safely and effectively without surgery.
                </p>
            </div>
            <div class="grid md:grid-cols-2 gap-8 items-center">
                <div class="space-y-6">
                    <div class="bg-blue-50 p-6 rounded-lg">
                        <h3 class="text-2xl font-semibold text-blue-800 mb-4">
                            <i class="fas fa-shield-alt mr-2"></i>
                            Safe & Effective
                        </h3>
                        <p class="text-gray-700">
                            Our advanced lithotripsy procedures use focused shock waves to break kidney stones 
                            into small fragments that can pass naturally through your urinary system.
                        </p>
                    </div>
                    <div class="bg-green-50 p-6 rounded-lg">
                        <h3 class="text-2xl font-semibold text-green-800 mb-4">
                            <i class="fas fa-clock mr-2"></i>
                            Quick Recovery
                        </h3>
                        <p class="text-gray-700">
                            Most patients can resume normal activities within 1-2 days. The procedure typically 
                            takes 45 minutes to 1 hour with minimal discomfort.
                        </p>
                    </div>
                </div>
                <div class="grid grid-cols-2 gap-4">
                    <img src="https://urologyaustin.com/wp-content/uploads/2018/08/iStock-506188713.jpg" 
                         alt="Lithotripsy Treatment" 
                         class="w-full h-48 object-cover rounded-lg shadow-lg hover-scale">
                    <img src="https://fairbanksurology.com/wp-content/uploads/2021/10/biomed-101-aug.jpg" 
                         alt="Medical Equipment" 
                         class="w-full h-48 object-cover rounded-lg shadow-lg hover-scale">
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="bg-gray-100 py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Our Lithotripsy Services</h2>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-lg hover-scale">
                    <div class="text-center mb-4">
                        <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-wave-square text-2xl text-blue-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800">ESWL Treatment</h3>
                    </div>
                    <p class="text-gray-600 text-center">
                        Extracorporeal Shock Wave Lithotripsy uses high-energy shock waves to break stones 
                        into tiny fragments that can be passed naturally.
                    </p>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-lg hover-scale">
                    <div class="text-center mb-4">
                        <div class="bg-red-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-laser-pointer text-2xl text-red-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800">Laser Lithotripsy</h3>
                    </div>
                    <p class="text-gray-600 text-center">
                        Advanced laser technology for precise stone fragmentation in kidney, bladder, 
                        ureter, or urethra with minimal invasiveness.
                    </p>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-lg hover-scale">
                    <div class="text-center mb-4">
                        <div class="bg-green-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-stethoscope text-2xl text-green-600"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800">Post-Treatment Care</h3>
                    </div>
                    <p class="text-gray-600 text-center">
                        Comprehensive follow-up care and monitoring to ensure successful stone 
                        passage and prevent recurrence.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Information Section -->
    <section class="bg-white py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Understanding Lithotripsy</h2>
            
            <div class="grid lg:grid-cols-2 gap-12">
                <div class="space-y-8">
                    <div class="section-fade">
                        <h3 class="text-2xl font-semibold text-blue-800 mb-4">What is Lithotripsy?</h3>
                        <p class="text-gray-700 leading-relaxed">
                            Lithotripsy is a non-invasive medical procedure that uses focused ultrasonic energy 
                            or shock waves to break kidney stones into smaller fragments. These fragments can 
                            then pass naturally through your urinary system, eliminating the need for surgery.
                        </p>
                    </div>

                    <div class="section-fade">
                        <h3 class="text-2xl font-semibold text-blue-800 mb-4">Procedure Details</h3>
                        <ul class="text-gray-700 space-y-2">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mr-2 mt-1"></i>
                                Duration: 45 minutes to 1 hour
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mr-2 mt-1"></i>
                                Outpatient procedure - no hospital stay required
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mr-2 mt-1"></i>
                                Minimal discomfort during treatment
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mr-2 mt-1"></i>
                                Uses fluoroscopy or ultrasound guidance
                            </li>
                        </ul>
                    </div>

                    <div class="section-fade">
                        <h3 class="text-2xl font-semibold text-blue-800 mb-4">Benefits & Recovery</h3>
                        <div class="bg-blue-50 p-6 rounded-lg">
                            <ul class="text-gray-700 space-y-2">
                                <li class="flex items-start">
                                    <i class="fas fa-heart text-red-500 mr-2 mt-1"></i>
                                    Non-invasive with minimal risk
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-running text-blue-500 mr-2 mt-1"></i>
                                    Resume activities within 1-2 days
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-tint text-blue-500 mr-2 mt-1"></i>
                                    Drink plenty of water to help pass fragments
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-calendar-check text-green-500 mr-2 mt-1"></i>
                                    Follow-up appointments ensure complete treatment
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="space-y-6">
                    <div class="section-fade">
                        <h3 class="text-2xl font-semibold text-blue-800 mb-4">When is Lithotripsy Recommended?</h3>
                        <div class="bg-gray-50 p-6 rounded-lg">
                            <ul class="text-gray-700 space-y-3">
                                <li class="flex items-start">
                                    <i class="fas fa-circle text-blue-500 mr-2 mt-1 text-xs"></i>
                                    Kidney stones smaller than 2 cm in diameter
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-circle text-blue-500 mr-2 mt-1 text-xs"></i>
                                    Stones causing pain or urinary blockage
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-circle text-blue-500 mr-2 mt-1 text-xs"></i>
                                    Stones that haven't passed naturally
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-circle text-blue-500 mr-2 mt-1 text-xs"></i>
                                    Patients who want to avoid surgery
                                </li>
                            </ul>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 gap-4">
                        <img src="https://www.healthtronics.com/wp-content/uploads/2021/07/Lithotripsy-for-Kidney-Stones-e1626711314533.png" 
                             alt="Lithotripsy Equipment" 
                             class="w-full h-48 object-cover rounded-lg shadow-lg">
                        <img src="https://www.dornier.com/americas/wp-content/uploads/sites/2/2020/06/1591873420124.jpg" 
                             alt="Medical Treatment" 
                             class="w-full h-48 object-cover rounded-lg shadow-lg">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Gallery -->
    <section class="bg-gray-100 py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Our Advanced Equipment</h2>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="https://assets.medpagetoday.net/media/images/51xxx/51716.jpg" 
                         alt="Lithotripsy Equipment" 
                         class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="font-semibold text-gray-800">Advanced Lithotripsy System</h3>
                        <p class="text-gray-600 text-sm">State-of-the-art equipment for precise treatment</p>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="https://www.drtimnathan-urology.com.au/sites/default/files/lithotripsy-for-stones-1.jpg" 
                         alt="Treatment Room" 
                         class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="font-semibold text-gray-800">Treatment Room</h3>
                        <p class="text-gray-600 text-sm">Comfortable and safe treatment environment</p>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="https://holycrossmedicalcenter.org/wp-content/uploads/2022/03/Stephen-Lucero-Lithotripsy-News.jpg" 
                         alt="Patient Care" 
                         class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="font-semibold text-gray-800">Patient Care</h3>
                        <p class="text-gray-600 text-sm">Dedicated medical professionals ensuring comfort</p>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="https://www.kidneystonestreatments.co.uk/wp-content/uploads/shockwave-lithotripsy.webp" 
                         alt="Shock Wave Therapy" 
                         class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="font-semibold text-gray-800">Shock Wave Therapy</h3>
                        <p class="text-gray-600 text-sm">Non-invasive shock wave treatment technology</p>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="https://lirp.cdn-website.com/7287c406/dms3rep/multi/opt/Kidney-Stones-ESWL-640w.jpg" 
                         alt="ESWL Treatment" 
                         class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="font-semibold text-gray-800">ESWL Treatment</h3>
                        <p class="text-gray-600 text-sm">Extracorporeal Shock Wave Lithotripsy in action</p>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="https://www.ypo.education/images/player_image/19-09-09-17-43-04_1239660205_thumbnail_large.png" 
                         alt="Medical Procedure" 
                         class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="font-semibold text-gray-800">Medical Procedure</h3>
                        <p class="text-gray-600 text-sm">Professional medical treatment process</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="medical-gradient text-white py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12">Get in Touch</h2>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div class="space-y-6">
                    <h3 class="text-2xl font-semibold mb-4">Contact Information</h3>
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <i class="fab fa-whatsapp text-2xl mr-4 text-green-400"></i>
                            <div>
                                <p class="text-lg font-semibold">WhatsApp</p>
                                <a href="https://wa.me/+923339451288" class="text-blue-200 hover:text-white">+92 333 9451288</a>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-phone text-2xl mr-4 text-blue-300"></i>
                            <div>
                                <p class="text-lg font-semibold">Phone</p>
                                <p class="text-blue-200">+92 333 9451288</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-hospital text-2xl mr-4 text-blue-300"></i>
                            <div>
                                <p class="text-lg font-semibold">Clinic</p>
                                <p class="text-blue-200">Awan Kidney Center Lithotripsy</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="space-y-6">
                    <h3 class="text-2xl font-semibold mb-4">Why Choose Us?</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mr-3 mt-1"></i>
                            <p>Experienced medical professionals</p>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mr-3 mt-1"></i>
                            <p>State-of-the-art lithotripsy equipment</p>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mr-3 mt-1"></i>
                            <p>Comprehensive patient care</p>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mr-3 mt-1"></i>
                            <p>Quick and effective treatment</p>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mr-3 mt-1"></i>
                            <p>Minimal recovery time</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="https://wa.me/+923339451288" target="_blank" 
                   class="inline-block bg-green-500 hover:bg-green-600 text-white px-8 py-4 rounded-lg font-semibold text-lg transition-colors duration-300">
                    <i class="fab fa-whatsapp mr-2 text-xl"></i>
                    Schedule Your Consultation
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="text-center">
                <h3 class="text-2xl font-bold mb-4">Awan Kidney Center Lithotripsy</h3>
                <p class="text-gray-400 mb-4">Advanced Kidney Stone Treatment Center</p>
                <div class="flex justify-center space-x-6">
                    <a href="https://wa.me/+923339451288" target="_blank" 
                       class="text-gray-400 hover:text-green-400 transition-colors">
                        <i class="fab fa-whatsapp text-2xl"></i>
                    </a>
                    <a href="tel:+923339451288" 
                       class="text-gray-400 hover:text-blue-400 transition-colors">
                        <i class="fas fa-phone text-2xl"></i>
                    </a>
                </div>
                <p class="text-gray-500 mt-6">© 2024 Awan Kidney Center Lithotripsy. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/+923339451288" target="_blank" 
       class="whatsapp-float bg-green-500 hover:bg-green-600 text-white p-4 rounded-full shadow-lg transition-colors duration-300">
        <i class="fab fa-whatsapp text-2xl"></i>
    </a>

    <script>
        // Fade in animation for sections
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.section-fade').forEach(el => {
            observer.observe(el);
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
