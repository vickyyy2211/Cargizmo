# Cargizmo<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cargizmo - Premium Car Accessories Dropshipping</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-section {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://placehold.co/1920x1080');
            background-size: cover;
            background-position: center;
            min-height: 500px;
        }
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            transition: all 0.3s ease;
        }
        .testimonial-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(5px);
        }
        .newsletter-section {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://placehold.co/1920x600');
            background-size: cover;
            background-position: center;
        }
        .top-banner {
            background: linear-gradient(90deg, #1a237e, #283593);
        }
        .discount-badge {
            position: absolute;
            top: 10px;
            right: 10px;
            background: #e53935;
            color: white;
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 12px;
            font-weight: bold;
        }
    </style>
</head>
<body class="font-sans bg-gray-50">
    <!-- Top Banner -->
    <div class="top-banner text-white text-center py-2 text-sm">
        🚚 Free shipping on orders over $50 | 📞 24/7 Support: 1-800-CARGIZMO
    </div>

    <!-- Navigation -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <img src="https://placehold.co/50x50" alt="Cargizmo logo - modern automotive design with gears motif" class="h-8 w-auto">
                        <span class="ml-2 text-xl font-bold text-gray-900">Cargizmo</span>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-center space-x-4">
                        <a href="#" class="text-gray-900 hover:text-blue-600 px-3 py-2 text-sm font-medium">Home</a>
                        <a href="#" class="text-gray-500 hover:text-blue-600 px-3 py-2 text-sm font-medium">Shop</a>
                        <a href="#" class="text-gray-500 hover:text-blue-600 px-3 py-2 text-sm font-medium">New Arrivals</a>
                        <a href="#" class="text-gray-500 hover:text-blue-600 px-3 py-2 text-sm font-medium">Best Sellers</a>
                        <a href="#" class="text-gray-500 hover:text-blue-600 px-3 py-2 text-sm font-medium">Deals</a>
                        <a href="#" class="text-gray-500 hover:text-blue-600 px-3 py-2 text-sm font-medium">About</a>
                    </div>
                </div>
                <div class="flex items-center">
                    <button class="p-2 text-gray-400 hover:text-gray-500">
                        <i class="fas fa-search"></i>
                    </button>
                    <div class="relative">
                        <button class="p-2 text-gray-400 hover:text-gray-500">
                            <i class="fas fa-user"></i>
                        </button>
                        <div class="absolute hidden bg-white shadow-lg rounded mt-2 py-2 w-48 right-0">
                            <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-blue-100">My Account</a>
                            <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-blue-100">Order History</a>
                            <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-blue-100">Wishlist</a>
                            <a href="#" class="block px-4 py-2 text-gray-800 hover:bg-blue-100">Logout</a>
                        </div>
                    </div>
                    <button class="p-2 text-gray-400 hover:text-gray-500 relative">
                        <i class="fas fa-shopping-cart"></i>
                        <span class="absolute top-0 right-0 bg-blue-600 text-white text-xs rounded-full h-5 w-5 flex items-center justify-center">3</span>
                    </button>
                    <button class="md:hidden p-2 text-gray-400 hover:text-gray-500">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Mobile Menu -->
    <div class="hidden mobile-menu md:hidden bg-white shadow-lg">
        <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
            <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Home</a>
            <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Shop</a>
            <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">New Arrivals</a>
            <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Best Sellers</a>
            <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Deals</a>
            <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">About</a>
        </div>
    </div>

    <!-- Hero Section -->
    <div class="hero-section flex items-center justify-center text-center text-white relative">
        <div class="absolute top-4 right-4">
            <span class="bg-yellow-400 text-black px-3 py-1 rounded-full text-sm font-bold">LIMITED TIME OFFER</span>
        </div>
        <div class="max-w-2xl mx-auto px-4">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Upgrade Your Ride With Cargizmo</h1>
            <p class="text-xl mb-8">Premium automotive accessories at wholesale prices with direct shipping to your customers</p>
            <div class="flex justify-center space-x-4">
                <button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-md text-lg transition duration-300">Shop Now</button>
                <button class="bg-transparent hover:bg-white hover:text-black text-white font-bold py-3 px-6 rounded-md text-lg border-2 border-white transition duration-300">Learn More</button>
            </div>
        </div>
    </div>

    <!-- Trust Badges -->
    <div class="bg-gray-100 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
                <div class="flex flex-col items-center">
                    <i class="fas fa-truck text-3xl text-blue-600 mb-2"></i>
                    <h3 class="font-semibold">Free Shipping</h3>
                    <p class="text-sm text-gray-600">On orders over $50</p>
                </div>
                <div class="flex flex-col items-center">
                    <i class="fas fa-undo text-3xl text-blue-600 mb-2"></i>
                    <h3 class="font-semibold">Easy Returns</h3>
                    <p class="text-sm text-gray-600">30-day guarantee</p>
                </div>
                <div class="flex flex-col items-center">
                    <i class="fas fa-lock text-3xl text-blue-600 mb-2"></i>
                    <h3 class="font-semibold">Secure Checkout</h3>
                    <p class="text-sm text-gray-600">SSL protected</p>
                </div>
                <div class="flex flex-col items-center">
                    <i class="fas fa-headset text-3xl text-blue-600 mb-2"></i>
                    <h3 class="font-semibold">24/7 Support</h3>
                    <p class="text-sm text-gray-600">Dedicated team</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Featured Categories -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <h2 class="text-3xl font-bold text-center mb-4">Shop By Category</h2>
        <p class="text-gray-600 text-center mb-12">Discover our wide range of automotive products</p>
        
        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
            <a href="#" class="category-card bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition duration-300 relative">
                <div class="discount-badge">20% OFF</div>
                <img src="https://placehold.co/400x300" alt="Premium car audio systems with touchscreen displays" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h3 class="font-semibold text-lg mb-2">Audio Systems</h3>
                    <p class="text-sm text-gray-600 mb-2">Upgrade your sound system</p>
                    <span class="text-blue-600 font-medium">Explore →</span>
                </div>
            </a>
            
            <a href="#" class="category-card bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition duration-300">
                <img src="https://placehold.co/400x300" alt="LED car lighting kits with multiple color options" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h3 class="font-semibold text-lg mb-2">Lighting</h3>
                    <p class="text-sm text-gray-600 mb-2">Illuminate your journey</p>
                    <span class="text-blue-600 font-medium">Explore →</span>
                </div>
            </a>
            
            <a href="#" class="category-card bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition duration-300">
                <div class="discount-badge">NEW</div>
                <img src="https://placehold.co/400x300" alt="Luxury car seat covers and interior accessories" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h3 class="font-semibold text-lg mb-2">Interior</h3>
                    <p class="text-sm text-gray-600 mb-2">Comfort and style</p>
                    <span class="text-blue-600 font-medium">Explore →</span>
                </div>
            </a>
            
            <a href="#" class="category-card bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition duration-300">
                <img src="https://placehold.co/400x300" alt="Performance car parts and tuning accessories" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h3 class="font-semibold text-lg mb-2">Performance</h3>
                    <p class="text-sm text-gray-600 mb-2">Boost your car's power</p>
                    <span class="text-blue-600 font-medium">Explore →</span>
                </div>
            </a>
        </div>
    </div>

    <!-- Featured Products -->
    <div class="bg-gray-100 py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-4">Featured Products</h2>
            <p class="text-gray-600 text-center mb-12">Our most popular automotive accessories</p>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition duration-300 relative">
                    <div class="discount-badge">25% OFF</div>
                    <img src="https://placehold.co/400x300" alt="Wireless CarPlay Android Auto adapter with touchscreen interface" class="w-full h-56 object-cover">
                    <div classp-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-semibold text-lg mb-1">Smart Touchscreen CarPlay</h3>
                                <div class="flex items-center mb-2">
                                    <div class="flex text-yellow-400">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star-half-alt"></i>
                                    </div>
                                    <span class="text-gray-600 text-sm ml-2">(142)</span>
                                </div>
                            </div>
                            <button class="text-gray-400 hover:text-red-500">
                                <i class="far fa-heart"></i>
                            </button>
                        </div>
                        <div class="flex items-center">
                            <span class="text-xl font-bold text-gray-900">$129.99</span>
                            <span class="text-sm text-gray-500 line-through ml-2">$159.99</span>
                        </div>
                        <button class="w-full mt-4 bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-md transition duration-300">
                            Add to Cart
                        </button>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition duration-300">
                    <img src="https://placehold.co/400x300" alt="LED headlight conversion kit with bright white illumination" class="w-full h-56 object-cover">
                    <div classp-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-semibold text-lg mb-1">UltraBright LED Headlights</h3>
                                <div class="flex items-center mb-2">
                                    <div class="flex text-yellow-400">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="far fa-star"></i>
                                    </div>
                                    <span class="text-gray-600 text-sm ml-2">(87)</span>
                                </div>
                            </div>
                            <button class="text-gray-400 hover:text-red-500">
                                <i class="far fa-heart"></i>
                            </button>
                        </div>
                        <div class="flex items-center">
                            <span class="text-xl font-bold text-gray-900">$59.99</span>
                        </div>
                        <button class="w-full mt-4 bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-md transition duration-300">
                            Add to Cart
                        </button>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition duration-300">
                    <img src="https://placehold.co/400x300" alt="Car vacuum cleaner with multiple attachments and wireless operation" class="w-full h-56 object-cover">
                    <div classp-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-semibold text-lg mb-1">Wireless Car Vacuum</h3>
                                <div class="flex items-center mb-2">
                                    <div class="flex text-yellow-400">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
