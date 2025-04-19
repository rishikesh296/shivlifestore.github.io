<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SHIV LIFE STORE - आपका संपूर्ण शॉपिंग डेस्टिनेशन</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
        }
        .category-card:hover {
            transform: translateY(-5px);
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: scale(1.03);
            transition: transform 0.3s ease;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-blue-900 text-white shadow-lg">
        <div class="container mx-auto px-4 py-3">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <h1 class="text-3xl font-bold">SHIV LIFE STORE</h1>
                    <p class="ml-3 text-blue-200 hidden md:block">आपका संपूर्ण शॉपिंग डेस्टिनेशन</p>
                </div>
                <div class="hidden md:flex space-x-6 items-center">
                    <a href="#" class="hover:text-blue-200"><i class="fas fa-search mr-1"></i> खोजें</a>
                    <a href="#" class="hover:text-blue-200"><i class="fas fa-user mr-1"></i> खाता</a>
                    <a href="#" class="hover:text-blue-200"><i class="fas fa-heart mr-1"></i> विशलिस्ट</a>
                    <a href="#" class="hover:text-blue-200 relative">
                        <i class="fas fa-shopping-cart mr-1"></i> कार्ट
                        <span class="absolute -top-2 -right-2 bg-red-500 text-white rounded-full w-5 h-5 flex items-center justify-center text-xs">0</span>
                    </a>
                </div>
                <div class="md:hidden">
                    <button class="text-white"><i class="fas fa-bars text-xl"></i></button>
                </div>
            </div>
        </div>
        
        <!-- Navigation -->
        <nav class="bg-blue-800 py-2">
            <div class="container mx-auto px-4">
                <ul class="flex flex-wrap space-x-1 md:space-x-8 justify-center text-sm md:text-base">
                    <li><a href="#" class="hover:text-blue-200 px-2 py-1">होम</a></li>
                    <li><a href="#categories" class="hover:text-blue-200 px-2 py-1">श्रेणियां</a></li>
                    <li><a href="#featured" class="hover:text-blue-200 px-2 py-1">फीचर्ड प्रोडक्ट्स</a></li>
                    <li><a href="#new-arrivals" class="hover:text-blue-200 px-2 py-1">नए आइटम</a></li>
                    <li><a href="#offers" class="hover:text-blue-200 px-2 py-1">ऑफर्स</a></li>
                    <li><a href="#reviews" class="hover:text-blue-200 px-2 py-1">ग्राहक समीक्षा</a></li>
                    <li><a href="#contact" class="hover:text-blue-200 px-2 py-1">संपर्क</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- Hero Banner -->
    <section class="bg-gradient-to-r from-blue-900 to-purple-900 text-white py-12 md:py-20">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 text-center md:text-left mb-8 md:mb-0">
                <h2 class="text-3xl md:text-5xl font-bold mb-4">SHIV LIFE STORE में आपका स्वागत है</h2>
                <p class="text-lg md:text-xl mb-6">आपकी सभी जरूरतों के लिए एक ही जगह - कपड़े, इलेक्ट्रॉनिक्स, घरेलू सामान और बहुत कुछ!</p>
                <div class="flex flex-col sm:flex-row justify-center md:justify-start space-y-3 sm:space-y-0 sm:space-x-4">
                    <a href="#categories" class="bg-yellow-500 hover:bg-yellow-600 text-gray-900 font-bold py-3 px-6 rounded-lg transition duration-300">अभी खरीदारी करें</a>
                    <a href="#featured" class="bg-transparent border-2 border-white hover:bg-white hover:text-blue-900 font-bold py-3 px-6 rounded-lg transition duration-300">विशेष ऑफर्स</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="bg-white p-2 rounded-lg shadow-2xl transform rotate-3 w-full max-w-lg">
                    <div class="bg-gray-200 h-48 md:h-64 rounded flex items-center justify-center">
                        <i class="fas fa-shopping-bag text-7xl text-gray-400"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Categories -->
    <section id="categories" class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">हमारी श्रेणियां</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-6">
                <!-- Category 1: Clothing -->
                <div class="category-card bg-gradient-to-br from-red-50 to-red-100 p-6 rounded-xl shadow-md text-center transition duration-300">
                    <div class="bg-red-200 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-tshirt text-red-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">कपड़े</h3>
                    <p class="text-gray-600 mb-4">पुरुष, महिला और बच्चों के लिए नवीनतम फैशन</p>
                    <a href="#" class="text-red-600 hover:text-red-800 font-medium">अभी खरीदें <i class="fas fa-chevron-right text-xs ml-1"></i></a>
                </div>

                <!-- Category 2: Electronics -->
                <div class="category-card bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl shadow-md text-center transition duration-300">
                    <div class="bg-blue-200 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-laptop text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">इलेक्ट्रॉनिक्स</h3>
                    <p class="text-gray-600 mb-4">नवीनतम गैजेट्स और इलेक्ट्रॉनिक उपकरण</p>
                    <a href="#" class="text-blue-600 hover:text-blue-800 font-medium">अभी खरीदें <i class="fas fa-chevron-right text-xs ml-1"></i></a>
                </div>

                <!-- Category 3: Home Goods -->
                <div class="category-card bg-gradient-to-br from-green-50 to-green-100 p-6 rounded-xl shadow-md text-center transition duration-300">
                    <div class="bg-green-200 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-home text-green-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">घरेलू सामान</h3>
                    <p class="text-gray-600 mb-4">आपके घर के लिए उत्कृष्ट उत्पाद</p>
                    <a href="#" class="text-green-600 hover:text-green-800 font-medium">अभी खरीदें <i class="fas fa-chevron-right text-xs ml-1"></i></a>
                </div>

                <!-- Category 4: Food Items -->
                <div class="category-card bg-gradient-to-br from-yellow-50 to-yellow-100 p-6 rounded-xl shadow-md text-center transition duration-300">
                    <div class="bg-yellow-200 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-utensils text-yellow-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">खाद्य पदार्थ</h3>
                    <p class="text-gray-600 mb-4">ताजा और स्वादिष्ट खाद्य उत्पाद</p>
                    <a href="#" class="text-yellow-600 hover:text-yellow-800 font-medium">अभी खरीदें <i class="fas fa-chevron-right text-xs ml-1"></i></a>
                </div>

                <!-- Category 5: Handicrafts -->
                <div class="category-card bg-gradient-to-br from-purple-50 to-purple-100 p-6 rounded-xl shadow-md text-center transition duration-300">
                    <div class="bg-purple-200 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-paint-brush text-purple-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">हस्तशिल्प</h3>
                    <p class="text-gray-600 mb-4">हाथ से बने अनूठे और सुंदर कलाकृति</p>
                    <a href="#" class="text-purple-600 hover:text-purple-800 font-medium">अभी खरीदें <i class="fas fa-chevron-right text-xs ml-1"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Products -->
    <section id="featured" class="py-12 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-3">फीचर्ड प्रोडक्ट्स</h2>
            <p class="text-center text-gray-600 mb-10">हमारे ग्राहकों द्वारा सबसे पसंद किए जाने वाले उत्पाद</p>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="h-48 bg-gray-200 flex items-center justify-center">
                        <i class="fas fa-tshirt text-5xl text-gray-400"></i>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-center mb-2">
                            <span class="bg-red-100 text-red-800 text-xs font-semibold px-2 py-1 rounded">कपड़े</span>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">प्रीमियम कॉटन टी-शर्ट</h3>
                        <p class="text-gray-600 text-sm mb-3">100% शुद्ध कॉटन से बनी, आरामदायक फिट</p>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-400 line-through">₹899</span>
                                <span class="font-bold text-lg ml-1">₹599</span>
                            </div>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 rounded-lg text-sm">कार्ट में जोड़ें</button>
                        </div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="h-48 bg-gray-200 flex items-center justify-center">
                        <i class="fas fa-headphones text-5xl text-gray-400"></i>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-center mb-2">
                            <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2 py-1 rounded">इलेक्ट्रॉनिक्स</span>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">वायरलेस हेडफोन</h3>
                        <p class="text-gray-600 text-sm mb-3">नॉइज कैंसलेशन के साथ, 20 घंटे की बैटरी लाइफ</p>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-400 line-through">₹2,499</span>
                                <span class="font-bold text-lg ml-1">₹1,799</span>
                            </div>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 rounded-lg text-sm">कार्ट में जोड़ें</button>
                        </div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="h-48 bg-gray-200 flex items-center justify-center">
                        <i class="fas fa-couch text-5xl text-gray-400"></i>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-center mb-2">
                            <span class="bg-green-100 text-green-800 text-xs font-semibold px-2 py-1 rounded">घरेलू सामान</span>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">लग्जरी कुशन सेट</h3>
                        <p class="text-gray-600 text-sm mb-3">4 मखमल के कुशन, विभिन्न रंगों में उपलब्ध</p>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-400 line-through">₹1,299</span>
                                <span class="font-bold text-lg ml-1">₹999</span>
                            </div>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 rounded-lg text-sm">कार्ट में जोड़ें</button>
                        </div>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="h-48 bg-gray-200 flex items-center justify-center">
                        <i class="fas fa-gift text-5xl text-gray-400"></i>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-center mb-2">
                            <span class="bg-purple-100 text-purple-800 text-xs font-semibold px-2 py-1 rounded">हस्तशिल्प</span>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                                <i class="far fa-star"></i>
                            </div>
                        </div>
                        <h3 class="text-lg font-semibold mb-1">हाथ से बनी मिट्टी के दीये</h3>
                        <p class="text-gray-600 text-sm mb-3">सेट ऑफ 6, फेस्टिवल सीजन के लिए परफेक्ट</p>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-400 line-through">₹499</span>
                                <span class="font-bold text-lg ml-1">₹349</span>
                            </div>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 rounded-lg text-sm">कार्ट में जोड़ें</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- New Arrivals -->
    <section id="new-arrivals" class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-3">नए आइटम</h2>
            <p class="text-center text-gray-600 mb-10">हमारे नवीनतम प्रोडक्ट्स देखें</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- New Item 1 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden flex">
                    <div class="w-1/3 bg-gray-200 flex items-center justify-center">
                        <i class="fas fa-mobile-alt text-4xl text-gray-400"></i>
                    </div>
                    <div class="w-2/3 p-4">
                        <span class="bg-yellow-100 text-yellow-800 text-xs font-semibold px-2 py-1 rounded mb-2 inline-block">नया</span>
                        <h3 class="text-lg font-semibold mb-1">स्मार्टफोन मॉडल X</h3>
                        <p class="text-gray-600 text-sm mb-3">8GB RAM, 128GB स्टोरेज, क्वाड कैमरा</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-lg">₹14,999</span>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 rounded-lg text-sm">अधिक जानें</button>
                        </div>
                    </div>
                </div>

                <!-- New Item 2 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden flex">
                    <div class="w-1/3 bg-gray-200 flex items-center justify-center">
                        <i class="fas fa-blender text-4xl text-gray-400"></i>
                    </div>
                    <div class="w-2/3 p-4">
                        <span class="bg-yellow-100 text-yellow-800 text-xs font-semibold px-2 py-1 rounded mb-2 inline-block">नया</span>
                        <h3 class="text-lg font-semibold mb-1">हाई-स्पीड मिक्सर ग्राइंडर</h3>
                        <p class="text-gray-600 text-sm mb-3">750W पावर, 5 स्पीड सेटिंग्स, 3 जार</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-lg">₹3,499</span>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 rounded-lg text-sm">अधिक जानें</button>
                        </div>
                    </div>
                </div>

                <!-- New Item 3 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden flex">
                    <div class="w-1/3 bg-gray-200 flex items-center justify-center">
                        <i class="fas fa-shoe-prints text-4xl text-gray-400"></i>
                    </div>
                    <div class="w-2/3 p-4">
                        <span class="bg-yellow-100 text-yellow-800 text-xs font-semibold px-2 py-1 rounded mb-2 inline-block">नया</span>
                        <h3 class="text-lg font-semibold mb-1">स्पोर्ट्स रनिंग शूज</h3>
                        <p class="text-gray-600 text-sm mb-3">लाइटवेट, एयर कुशनिंग, नॉन-स्लिप सोल</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-lg">₹2,199</span>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white px-3 py-1 rounded-lg text-sm">अधिक जानें</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Special Offers -->
    <section id="offers" class="py-12 bg-gradient-to-r from-yellow-500 to-red-500 text-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">विशेष ऑफर्स</h2># shivlifestore.github.io
