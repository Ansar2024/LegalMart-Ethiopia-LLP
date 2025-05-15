<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LegalMart Ethiopia LLP - Premier Legal Services</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Custom CSS */
        .hero-gradient {
            background: linear-gradient(135deg, #1e3a8a 0%, #2563eb 50%, #3b82f6 100%);
        }
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .testimonial-card {
            transition: all 0.3s ease;
        }
        .testimonial-card:hover {
            transform: scale(1.05);
        }
        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: 0;
            left: 0;
            background-color: #3b82f6;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
        .animate-float {
            animation: float 3s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        .payment-method {
            filter: grayscale(100%);
            transition: all 0.3s ease;
        }
        .payment-method:hover {
            filter: grayscale(0%);
            transform: scale(1.1);
        }
        .telelaw-icon {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <i class="fas fa-balance-scale text-blue-600 text-3xl mr-2"></i>
                        <span class="text-xl font-bold text-blue-600">LegalMart Ethiopia LLP</span>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-center space-x-8">
                        <a href="#home" class="nav-link text-gray-900 px-3 py-2 text-sm font-medium">Home</a>
                        <a href="#services" class="nav-link text-gray-900 px-3 py-2 text-sm font-medium">Services</a>
                        <a href="#about" class="nav-link text-gray-900 px-3 py-2 text-sm font-medium">About</a>
                        <a href="#team" class="nav-link text-gray-900 px-3 py-2 text-sm font-medium">Team</a>
                        <a href="#contact" class="nav-link text-gray-900 px-3 py-2 text-sm font-medium">Contact</a>
                        <a href="#telelaw" class="nav-link text-gray-900 px-3 py-2 text-sm font-medium">Tele Law</a>
                        <a href="#appointment" class="bg-blue-600 text-white px-4 py-2 rounded-md text-sm font-medium hover:bg-blue-700 transition duration-300">Book Consultation</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-gray-900 focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#home" class="block px-3 py-2 text-base font-medium text-gray-900 hover:bg-gray-100">Home</a>
                <a href="#services" class="block px-3 py-2 text-base font-medium text-gray-900 hover:bg-gray-100">Services</a>
                <a href="#about" class="block px-3 py-2 text-base font-medium text-gray-900 hover:bg-gray-100">About</a>
                <a href="#team" class="block px-3 py-2 text-base font-medium text-gray-900 hover:bg-gray-100">Team</a>
                <a href="#contact" class="block px-3 py-2 text-base font-medium text-gray-900 hover:bg-gray-100">Contact</a>
                <a href="#telelaw" class="block px-3 py-2 text-base font-medium text-gray-900 hover:bg-gray-100">Tele Law</a>
                <a href="#appointment" class="block px-3 py-2 text-base font-medium text-white bg-blue-600 rounded-md">Book Consultation</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-gradient text-white py-20 md:py-32">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold leading-tight mb-6">Your Trusted Legal Partner in Ethiopia</h1>
                    <p class="text-xl md:text-2xl mb-8 opacity-90">Providing exceptional legal services with integrity, professionalism, and a commitment to excellence.</p>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <a href="#contact" class="bg-white text-blue-600 px-6 py-3 rounded-md text-lg font-semibold hover:bg-gray-100 transition duration-300 text-center">Get in Touch</a>
                        <a href="#services" class="border-2 border-white text-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-white hover:text-blue-600 transition duration-300 text-center">Our Services</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <img src="https://images.unsplash.com/photo-1589829545856-d10d557cf95f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Legal Services" class="rounded-lg shadow-2xl animate-float max-w-full h-auto">
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-gray-50 py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 text-center">
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <div class="text-blue-600 text-4xl font-bold mb-2">15+</div>
                    <div class="text-gray-600 text-lg">Years Experience</div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <div class="text-blue-600 text-4xl font-bold mb-2">500+</div>
                    <div class="text-gray-600 text-lg">Clients Served</div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <div class="text-blue-600 text-4xl font-bold mb-2">98%</div>
                    <div class="text-gray-600 text-lg">Success Rate</div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <div class="text-blue-600 text-4xl font-bold mb-2">24/7</div>
                    <div class="text-gray-600 text-lg">Client Support</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tele Law Section -->
    <section id="telelaw" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <div class="flex items-center mb-6">
                        <div class="bg-blue-100 p-4 rounded-full mr-4 telelaw-icon">
                            <i class="fas fa-video text-blue-600 text-2xl"></i>
                        </div>
                        <h2 class="text-3xl md:text-4xl font-bold text-gray-900">Tele Law Services</h2>
                    </div>
                    <div class="w-20 h-1 bg-blue-600 mb-6"></div>
                    <p class="text-gray-600 mb-6 text-lg">Access legal expertise from anywhere in Ethiopia through our secure video consultation platform. Our Tele Law services provide convenient, confidential legal advice without the need for in-person visits.</p>
                    <div class="space-y-4 mb-8">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-check-circle text-blue-500"></i>
                            </div>
                            <p class="ml-3 text-gray-600">Secure, encrypted video consultations</p>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-check-circle text-blue-500"></i>
                            </div>
                            <p class="ml-3 text-gray-600">Same-day appointments available</p>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-check-circle text-blue-500"></i>
                            </div>
                            <p class="ml-3 text-gray-600">Document sharing and e-signature capabilities</p>
                        </div>
                    </div>
                    <a href="#appointment" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-blue-600 hover:bg-blue-700">
                        Schedule Tele Consultation
                        <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>
                <div class="md:w-1/2">
                    <div class="bg-gray-50 p-8 rounded-lg shadow-lg border border-gray-200">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-6">How Tele Law Works</h3>
                        <div class="space-y-6">
                            <div class="flex">
                                <div class="flex-shrink-0">
                                    <div class="flex items-center justify-center h-12 w-12 rounded-full bg-blue-100 text-blue-600 font-bold">1</div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Book Your Session</h4>
                                    <p class="mt-1 text-gray-600">Schedule a convenient time for your video consultation.</p>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="flex-shrink-0">
                                    <div class="flex items-center justify-center h-12 w-12 rounded-full bg-blue-100 text-blue-600 font-bold">2</div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Receive Confirmation</h4>
                                    <p class="mt-1 text-gray-600">Get a secure link and instructions for your session.</p>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="flex-shrink-0">
                                    <div class="flex items-center justify-center h-12 w-12 rounded-full bg-blue-100 text-blue-600 font-bold">3</div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Connect with Your Lawyer</h4>
                                    <p class="mt-1 text-gray-600">Join the video call at your scheduled time for expert legal advice.</p>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="flex-shrink-0">
                                    <div class="flex items-center justify-center h-12 w-12 rounded-full bg-blue-100 text-blue-600 font-bold">4</div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Follow-up Support</h4>
                                    <p class="mt-1 text-gray-600">Receive documentation and ongoing support as needed.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Our Legal Services</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto mb-6"></div>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Comprehensive legal solutions tailored to meet your specific needs with professionalism and expertise.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service Card 1 -->
                <div class="service-card bg-white rounded-lg shadow-lg overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-gavel text-blue-600 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900">Corporate Law</h3>
                        </div>
                        <p class="text-gray-600 mb-4">Expert guidance on corporate governance, compliance, mergers & acquisitions, and business structuring in Ethiopia.</p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Business Registration</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Contract Drafting</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Corporate Compliance</li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service Card 2 -->
                <div class="service-card bg-white rounded-lg shadow-lg overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-home text-blue-600 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900">Real Estate Law</h3>
                        </div>
                        <p class="text-gray-600 mb-4">Comprehensive legal services for property transactions, land disputes, and real estate development projects.</p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Property Transactions</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Lease Agreements</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Land Dispute Resolution</li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service Card 3 -->
                <div class="service-card bg-white rounded-lg shadow-lg overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-user-tie text-blue-600 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900">Employment Law</h3>
                        </div>
                        <p class="text-gray-600 mb-4">Protecting both employers and employees with expert advice on Ethiopian labor laws and regulations.</p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Employment Contracts</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Dispute Resolution</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Compliance Audits</li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service Card 4 -->
                <div class="service-card bg-white rounded-lg shadow-lg overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-passport text-blue-600 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900">Immigration Law</h3>
                        </div>
                        <p class="text-gray-600 mb-4">Navigating Ethiopia's immigration system for work permits, visas, and residency applications.</p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Work Permits</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Residence Permits</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Citizenship Applications</li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service Card 5 - Legal Health Audits -->
                <div class="service-card bg-white rounded-lg shadow-lg overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-clipboard-check text-blue-600 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900">Legal Health Audits</h3>
                        </div>
                        <p class="text-gray-600 mb-4">Comprehensive review of your legal compliance status to identify risks and ensure regulatory adherence.</p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Compliance Assessment</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Risk Identification</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Remediation Plan</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Ongoing Monitoring</li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service Card 6 - Tax and Financial Audits -->
                <div class="service-card bg-white rounded-lg shadow-lg overflow-hidden transition duration-300">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-file-invoice-dollar text-blue-600 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900">Tax & Financial Audits</h3>
                        </div>
                        <p class="text-gray-600 mb-4">Expert analysis of your financial records to ensure compliance with Ethiopian tax laws and regulations.</p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Tax Compliance Review</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Financial Record Analysis</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Audit Representation</li>
                            <li class="flex items-center"><i class="fas fa-check-circle text-blue-500 mr-2"></i> Tax Planning Strategies</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Payment Integration Section -->
    <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Secure Payment Options</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto mb-6"></div>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">We offer multiple secure payment methods for your convenience and peace of mind.</p>
            </div>
            
            <div class="bg-gray-50 rounded-xl p-8 shadow-inner">
                <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-6">
                    <div class="flex flex-col items-center justify-center p-4 bg-white rounded-lg shadow-sm payment-method">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/MasterCard_Logo.svg/1200px-MasterCard_Logo.svg.png" alt="Mastercard" class="h-12 object-contain">
                        <span class="mt-2 text-sm text-gray-600">Mastercard</span>
                    </div>
                    <div class="flex flex-col items-center justify-center p-4 bg-white rounded-lg shadow-sm payment-method">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Visa_Inc._logo.svg/1200px-Visa_Inc._logo.svg.png" alt="Visa" class="h-12 object-contain">
                        <span class="mt-2 text-sm text-gray-600">Visa</span>
                    </div>
                    <div class="flex flex-col items-center justify-center p-4 bg-white rounded-lg shadow-sm payment-method">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/American_Express_logo_%282018%29.svg/1200px-American_Express_logo_%282018%29.svg.png" alt="American Express" class="h-12 object-contain">
                        <span class="mt-2 text-sm text-gray-600">Amex</span>
                    </div>
                    <div class="flex flex-col items-center justify-center p-4 bg-white rounded-lg shadow-sm payment-method">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Logo_paypal.svg/1200px-Logo_paypal.svg.png" alt="PayPal" class="h-12 object-contain">
                        <span class="mt-2 text-sm text-gray-600">PayPal</span>
                    </div>
                    <div class="flex flex-col items-center justify-center p-4 bg-white rounded-lg shadow-sm payment-method">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Bank_of_Abyssinia_Logo.svg/1200px-Bank_of_Abyssinia_Logo.svg.png" alt="Bank of Abyssinia" class="h-12 object-contain">
                        <span class="mt-2 text-sm text-gray-600">Bank Transfer</span>
                    </div>
                    <div class="flex flex-col items-center justify-center p-4 bg-white rounded-lg shadow-sm payment-method">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d6/Telebirr_Logo.svg/1200px-Telebirr_Logo.svg.png" alt="Telebirr" class="h-12 object-contain">
                        <span class="mt-2 text-sm text-gray-600">Telebirr</span>
                    </div>
                </div>
                
                <div class="mt-12 bg-white rounded-lg shadow-lg p-8">
                    <h3 class="text-2xl font-semibold text-gray-900 mb-6">Payment Security</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                        <div>
                            <div class="flex items-start mb-6">
                                <div class="flex-shrink-0 mt-1">
                                    <i class="fas fa-lock text-blue-500 text-xl"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">SSL Encryption</h4>
                                    <p class="mt-1 text-gray-600">All transactions are protected with 256-bit SSL encryption to ensure your payment information is secure.</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <i class="fas fa-shield-alt text-blue-500 text-xl"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">PCI Compliance</h4>
                                    <p class="mt-1 text-gray-600">We adhere to strict PCI DSS standards for payment processing and data security.</p>
                                </div>
                            </div>
                        </div>
                        <div>
                            <div class="flex items-start mb-6">
                                <div class="flex-shrink-0 mt-1">
                                    <i class="fas fa-receipt text-blue-500 text-xl"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Instant Receipts</h4>
                                    <p class="mt-1 text-gray-600">Receive immediate payment confirmation and detailed invoices for all transactions.</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="flex-shrink-0 mt-1">
                                    <i class="fas fa-headset text-blue-500 text-xl"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Payment Support</h4>
                                    <p class="mt-1 text-gray-600">Our team is available to assist with any payment-related questions or issues.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">About LegalMart Ethiopia LLP</h2>
                    <div class="w-20 h-1 bg-blue-600 mb-6"></div>
                    <p class="text-gray-600 mb-6 text-lg">Founded in 2008, LegalMart Ethiopia LLP has grown to become one of the most respected full-service law firms in Ethiopia, known for our commitment to excellence, integrity, and client-focused service.</p>
                    <p class="text-gray-600 mb-6 text-lg">Our team of highly skilled attorneys brings together diverse expertise and deep knowledge of Ethiopian law to provide comprehensive legal solutions tailored to our clients' needs.</p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-check-circle text-blue-500"></i>
                            </div>
                            <p class="ml-3 text-gray-600">Ethiopian and international legal expertise</p>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-check-circle text-blue-500"></i>
                            </div>
                            <p class="ml-3 text-gray-600">Multilingual legal professionals</p>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <i class="fas fa-check-circle text-blue-500"></i>
                            </div>
                            <p class="ml-3 text-gray-600">Proven track record of success</p>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <div class="bg-white p-8 rounded-lg shadow-lg">
                        <h3 class="text-2xl font-semibold text-gray-900 mb-6">Why Choose Us?</h3>
                        <div class="space-y-6">
                            <div class="flex">
                                <div class="flex-shrink-0">
                                    <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-100 text-blue-600">
                                        <i class="fas fa-star"></i>
                                    </div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Excellence</h4>
                                    <p class="mt-1 text-gray-600">We maintain the highest standards of legal practice and professional ethics.</p>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="flex-shrink-0">
                                    <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-100 text-blue-600">
                                        <i class="fas fa-users"></i>
                                    </div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Client Focus</h4>
                                    <p class="mt-1 text-gray-600">Your success is our priority. We listen, understand, and deliver results.</p>
                                </div>
                            </div>
                            <div class="flex">
                                <div class="flex-shrink-0">
                                    <div class="flex items-center justify-center h-12 w-12 rounded-md bg-blue-100 text-blue-600">
                                        <i class="fas fa-lightbulb"></i>
                                    </div>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Innovation</h4>
                                    <p class="mt-1 text-gray-600">We combine traditional legal expertise with innovative approaches.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Meet Our Team</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto mb-6"></div>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Our team of dedicated legal professionals brings together diverse expertise and a shared commitment to excellence.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Team Member 1 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transition duration-300 hover:shadow-xl">
                    <img src="https://images.unsplash.com/photo-1560250097-0b93528c311a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Attorney" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900">Alemayehu Kebede</h3>
                        <p class="text-blue-600 mb-2">Managing Partner</p>
                        <p class="text-gray-600 mb-4">Specializing in corporate and commercial law with over 18 years of experience in Ethiopian legal practice.</p>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:text-blue-800"><i class="fab fa-linkedin"></i></a>
                            <a href="#" class="text-blue-600 hover:text-blue-800"><i class="fas fa-envelope"></i></a>
                        </div>
                    </div>
                </div>
                
                <!-- Team Member 2 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transition duration-300 hover:shadow-xl">
                    <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Attorney" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900">Selamawit Assefa</h3>
                        <p class="text-blue-600 mb-2">Senior Partner</p>
                        <p class="text-gray-600 mb-4">Expert in real estate and property law with extensive experience in land dispute resolution.</p>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:text-blue-800"><i class="fab fa-linkedin"></i></a>
                            <a href="#" class="text-blue-600 hover:text-blue-800"><i class="fas fa-envelope"></i></a>
                        </div>
                    </div>
                </div>
                
                <!-- Team Member 3 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden transition duration-300 hover:shadow-xl">
                    <img src="https://images.unsplash.com/photo-1568602471122-7832951cc4c5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Attorney" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900">Tewodros Mekonnen</h3>
                        <p class="text-blue-600 mb-2">Litigation Partner</p>
                        <p class="text-gray-600 mb-4">Seasoned litigator with a strong track record in civil and commercial disputes in Ethiopian courts.</p>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:text-blue-800"><i class="fab fa-linkedin"></i></a>
                            <a href="#" class="text-blue-600 hover:text-blue-800"><i class="fas fa-envelope"></i></a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <a href="#contact" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-blue-600 hover:bg-blue-700">
                    Meet the Full Team
                    <i class="fas fa-arrow-right ml-2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Client Testimonials</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto mb-6"></div>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">What our clients say about our services and commitment to excellence.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="testimonial-card bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <i class="fas fa-quote-left text-blue-500 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <div class="flex items-center">
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"LegalMart Ethiopia provided exceptional guidance during our business expansion into Ethiopia. Their knowledge of local laws and business practices was invaluable."</p>
                    <div class="flex items-center">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Client" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="text-lg font-medium text-gray-900">Michael Johnson</h4>
                            <p class="text-gray-500">CEO, GlobalTech Solutions</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial-card bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <i class="fas fa-quote-left text-blue-500 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <div class="flex items-center">
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"The team at LegalMart resolved our complex land dispute efficiently and professionally. Their attention to detail and strategic approach was impressive."</p>
                    <div class="flex items-center">
                        <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Client" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="text-lg font-medium text-gray-900">Sarah Williams</h4>
                            <p class="text-gray-500">Director, Addis Properties</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial-card bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <i class="fas fa-quote-left text-blue-500 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <div class="flex items-center">
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                            </div>
                        </div>
                    </
</html>
