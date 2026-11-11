<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title id="pageTitle">Budol Finds Hub | Curated Shopee Deals</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        shopee: {
                            DEFAULT: '#EE4D2D',
                            dark: '#D73211',
                            light: '#FFF0ED',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #f1f1f1; }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #94a3b8; }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased min-h-screen flex flex-col selection:bg-shopee selection:text-white">

    <!-- Top Banner Notification -->
    <div class="bg-gradient-to-r from-shopee to-orange-500 text-white text-xs sm:text-sm py-2 px-4 text-center font-medium shadow-sm flex items-center justify-center gap-3">
        <span>🔥 Exclusive Shopee Mega Deals & Daily Budol Finds!</span>
        <div class="flex items-center gap-2">
            <span class="underline cursor-pointer font-semibold" onclick="openAdminModal()">Admin & Full Code Export</span>
        </div>
    </div>

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between gap-4">
            <a href="./" class="flex items-center gap-2 group">
                <div class="w-10 h-10 rounded-xl bg-shopee flex items-center justify-center text-white font-bold text-xl shadow-md shadow-shopee/30 group-hover:scale-105 transition">
                    <i class="fa-solid fa-bag-shopping"></i>
                </div>
                <div>
                    <span class="font-extrabold text-lg sm:text-xl tracking-tight text-slate-900">Budol<span class="text-shopee">Hub</span></span>
                    <span class="block text-[10px] text-slate-500 font-medium uppercase tracking-wider">Shopee Static Affiliate</span>
                </div>
            </a>

            <!-- Search Bar (Desktop) -->
            <div id="searchContainer" class="hidden md:flex flex-1 max-w-md relative">
                <span class="absolute inset-y-0 left-0 pl-3.5 flex items-center pointer-events-none text-slate-400">
                    <i class="fa-solid fa-search"></i>
                </span>
                <input type="text" id="searchInput" placeholder="Search aesthetic finds, gadgets, kitchenware..." 
                    class="w-full pl-10 pr-4 py-2 bg-slate-100 border border-transparent rounded-full text-sm focus:outline-none focus:bg-white focus:border-shopee focus:ring-2 focus:ring-shopee/20 transition">
            </div>

            <!-- Header Action Buttons -->
            <div class="flex items-center gap-3">
                <button onclick="openAdminModal()" class="flex items-center gap-2 bg-slate-100 hover:bg-slate-200 text-slate-700 px-3.5 py-2 rounded-full text-xs sm:text-sm font-semibold transition">
                    <i class="fa-solid fa-gear text-shopee"></i>
                    <span class="hidden sm:inline">Manager & Code Export</span>
                </button>
                <a href="./#catalog" class="bg-shopee hover:bg-shopee-dark text-white px-4 py-2 rounded-full text-xs sm:text-sm font-semibold shadow-md shadow-shopee/20 transition transform active:scale-95">
                    Explore Deals
                </a>
            </div>
        </div>

        <!-- Search Bar (Mobile Display) -->
        <div id="mobileSearchContainer" class="md:hidden px-4 pb-3 pt-1 bg-white border-t border-slate-100">
            <div class="relative">
                <span class="absolute inset-y-0 left-0 pl-3.5 flex items-center pointer-events-none text-slate-400">
                    <i class="fa-solid fa-search"></i>
                </span>
                <input type="text" id="mobileSearchInput" placeholder="Search products..." 
                    class="w-full pl-10 pr-4 py-2 bg-slate-100 border border-transparent rounded-full text-sm focus:outline-none focus:bg-white focus:border-shopee focus:ring-2 focus:ring-shopee/20 transition">
            </div>
        </div>
    </header>

    <!-- Main Content Dynamic View -->
    <main id="mainContent" class="flex-1 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 w-full">
        <!-- Rendered via JavaScript -->
    </main>

    <!-- Admin & Full Code Export Manager Modal -->
    <div id="adminModal" class="fixed inset-0 z-50 bg-slate-900/50 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl shadow-2xl w-full max-w-3xl max-h-[90vh] flex flex-col overflow-hidden animate-in fade-in zoom-in duration-200">
            <div class="px-6 py-4 border-b border-slate-200 flex items-center justify-between bg-slate-50">
                <div class="flex items-center gap-2">
                    <div class="w-8 h-8 rounded-lg bg-shopee/10 text-shopee flex items-center justify-center font-bold">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 text-base">Product & Full Website Code Export</h3>
                        <p class="text-[11px] text-slate-500">Add products with SEO sub-pages and copy the entire updated website code</p>
                    </div>
                </div>
                <button onclick="closeAdminModal()" class="w-8 h-8 rounded-full bg-slate-200 hover:bg-slate-300 text-slate-600 flex items-center justify-center transition">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>

            <div class="p-6 overflow-y-auto flex-1 space-y-6">
                <!-- Add Product Form -->
                <div class="bg-slate-50 p-4 rounded-xl border border-slate-200">
                    <h4 class="font-bold text-slate-800 text-sm mb-3 flex items-center gap-2">
                        <i class="fa-solid fa-circle-plus text-shopee"></i> Add New Product
                    </h4>
                    <form id="addProductForm" onsubmit="handleAddNewProduct(event)" class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Product Title</label>
                            <input type="text" id="newTitle" required placeholder="e.g. Minimalist Coffee Mug" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Category</label>
                            <select id="newCategory" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                                <option value="Home Decor">Home Decor</option>
                                <option value="Tech & Gadgets">Tech & Gadgets</option>
                                <option value="Kitchen Essentials">Kitchen Essentials</option>
                                <option value="Fashion">Fashion</option>
                                <option value="Beauty & Skincare">Beauty & Skincare</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Price (₱)</label>
                            <input type="number" id="newPrice" required placeholder="349" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Original Price (₱)</label>
                            <input type="number" id="newOriginalPrice" placeholder="799" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Rating Star (e.g. 4.9)</label>
                            <input type="number" step="0.1" max="5" min="1" id="newRating" value="4.9" placeholder="4.9" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Sold Count (e.g. 1.2k, 500+)</label>
                            <input type="text" id="newSoldCount" value="100+" placeholder="1.2k" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Alt Text for Image SEO</label>
                            <input type="text" id="newAltText" placeholder="e.g. Nordic Minimalist Bedside Table Lamp with Wooden Stand" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Image URLs <span class="text-slate-400 font-normal">(Separate multiple image links with commas or newlines)</span></label>
                            <textarea id="newImages" rows="3" required placeholder="https://images.unsplash.com/photo-1..., https://images.unsplash.com/photo-2..." class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee font-mono"></textarea>
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold text-slate-600 mb-1">Shopee Affiliate Link</label>
                            <input type="url" id="newAffLink" required placeholder="https://shopee.ph/your-link" class="w-full text-xs p-2.5 bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-shopee">
                        </div>
                        <div class="sm:col-span-2 flex justify-end pt-2">
                            <button type="submit" class="bg-shopee hover:bg-shopee-dark text-white font-semibold px-5 py-2 rounded-lg text-xs shadow transition">
                                <i class="fa-solid fa-plus mr-1"></i> Add to Product List
                            </button>
                        </div>
                    </form>
                </div>

                <!-- Export Entire Website Code Section -->
                <div class="bg-orange-50/50 p-4 rounded-xl border border-orange-200 space-y-3">
                    <div class="flex items-center justify-between">
                        <div>
                            <h4 class="font-bold text-slate-900 text-sm">Copy Entire Website Source Code</h4>
                            <p class="text-xs text-slate-500">This updates automatically with your new products. Copy and replace your entire file in GitHub.</p>
                        </div>
                        <button onclick="copyFullWebsiteCode()" class="bg-shopee hover:bg-shopee-dark text-white px-4 py-2 rounded-lg text-xs font-bold shadow flex items-center gap-1.5 transition">
                            <i class="fa-solid fa-copy"></i> Copy All Code
                        </button>
                    </div>
                    <textarea id="fullCodeOutput" readonly rows="4" class="w-full font-mono text-[11px] p-3 bg-white border border-slate-300 rounded-lg focus:outline-none text-slate-700"></textarea>
                </div>

                <!-- Product Management List -->
                <div>
                    <h4 class="font-bold text-slate-800 text-sm mb-3">Current Products in Storage (<span id="adminProductCount">0</span>)</h4>
                    <div id="adminProductList" class="space-y-2 max-h-52 overflow-y-auto pr-1"></div>
                </div>
            </div>

            <div class="px-6 py-3 border-t border-slate-200 bg-slate-50 flex justify-between items-center text-xs text-slate-500">
                <span>Changes save to browser localStorage instantly</span>
                <button onclick="closeAdminModal()" class="bg-slate-800 hover:bg-slate-900 text-white px-4 py-2 rounded-lg font-semibold transition">Close Manager</button>
            </div>
        </div>
    </div>

    <!-- Notification Toast -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 bg-slate-900 text-white px-4 py-3 rounded-xl shadow-xl flex items-center gap-3 transform translate-y-20 opacity-0 transition-all duration-300 pointer-events-none">
        <i class="fa-solid fa-circle-check text-emerald-400"></i>
        <span id="toastMessage" class="text-xs sm:text-sm font-medium">Notification message</span>
    </div>

    <!-- Footer -->
    <footer class="bg-white border-t border-slate-200 mt-auto py-8 px-4 sm:px-6 lg:px-8 text-center text-xs text-slate-500 space-y-3">
        <div class="flex justify-center items-center gap-2 font-bold text-slate-800 text-base">
            <div class="w-6 h-6 rounded bg-shopee text-white flex items-center justify-center text-xs">
                <i class="fa-solid fa-bag-shopping"></i>
            </div>
            BudolHub Shopee Affiliate Storefront
        </div>
        <p class="max-w-md mx-auto">
            Disclaimer: We earn a small commission from qualifying purchases made through our Shopee affiliate links at no additional cost to you.
        </p>
        <p class="text-slate-400">&copy; 2026 BudolHub. All rights reserved.</p>
    </footer>

    <!-- Application JavaScript Logic -->
    <script>
        const defaultProducts = [
            {
                id: "nordic-minimalist-bedside-table-lamp",
                title: "Nordic Minimalist Bedside Table Lamp with Wooden Stand",
                category: "Home Decor",
                price: 349,
                originalPrice: 899,
                images: [
                    "https://images.unsplash.com/photo-1507473885765-e6ed057f782c?auto=format&fit=crop&w=600&q=80",
                    "https://images.unsplash.com/photo-1513519245088-0e12902e5a38?auto=format&fit=crop&w=600&q=80",
                    "https://images.unsplash.com/photo-1540932239986-30128078f3c5?auto=format&fit=crop&w=600&q=80"
                ],
                altText: "Nordic Minimalist Bedside Table Lamp with Wooden Stand",
                affLink: "https://shopee.ph",
                rating: 4.8,
                soldCount: "1.2k"
            },
            {
                id: "aesthetic-ergonomic-aluminum-laptop-stand",
                title: "Aesthetic Ergonomic Aluminum Laptop Stand Foldable",
                category: "Tech & Gadgets",
                price: 199,
                originalPrice: 599,
                images: [
                    "https://images.unsplash.com/photo-1527443224154-c4a3942d3acf?auto=format&fit=crop&w=600&q=80",
                    "https://images.unsplash.com/photo-1541807084-5c52b6b3adef?auto=format&fit=crop&w=600&q=80"
                ],
                altText: "Aesthetic Ergonomic Aluminum Laptop Stand Foldable",
                affLink: "https://shopee.ph",
                rating: 4.9,
                soldCount: "3.4k"
            },
            {
                id: "insulated-stainless-steel-tumbler",
                title: "Insulated Stainless Steel Tumbler 600ml with Straw",
                category: "Kitchen Essentials",
                price: 289,
                originalPrice: 650,
                images: [
                    "https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?auto=format&fit=crop&w=600&q=80",
                    "https://images.unsplash.com/photo-1544816155-12df9643f363?auto=format&fit=crop&w=600&q=80"
                ],
                altText: "Insulated Stainless Steel Tumbler 600ml with Straw",
                affLink: "https://shopee.ph",
                rating: 4.7,
                soldCount: "890"
            }
        ];

        let products = [];
        let currentCategory = 'All';
        let searchQuery = '';
        let currentSort = 'featured';
        let activeImageIndices = {};
        let singleProductActiveImgIdx = 0;

        window.addEventListener('DOMContentLoaded', () => {
            loadProducts();
            handleRouter();
            setupEventListeners();
        });

        function loadProducts() {
            const saved = localStorage.getItem('shopee_hub_products');
            if (saved) {
                try {
                    products = JSON.parse(saved);
                    if (!Array.isArray(products) || products.length === 0) {
                        products = defaultProducts;
                    } else {
                        products = products.map(p => {
                            if (!p.id) p.id = generateSlug(p.title || 'product');
                            if (!p.images && p.image) {
                                p.images = [p.image];
                            } else if (!p.images || !Array.isArray(p.images)) {
                                p.images = ['https://placehold.co/400x400/eee/666?text=Shopee+Find'];
                            }
                            return p;
                        });
                    }
                } catch(e) {
                    products = defaultProducts;
                }
            } else {
                products = defaultProducts;
                localStorage.setItem('shopee_hub_products', JSON.stringify(defaultProducts));
            }
        }

        function generateSlug(text) {
            return text.toLowerCase().replace(/[^\w ]+/g, '').replace(/ +/g, '-');
        }

        function saveProductsToStorage() {
            localStorage.setItem('shopee_hub_products', JSON.stringify(products));
            updateFullCodeField();
        }

        function setupEventListeners() {
            const searchInput = document.getElementById('searchInput');
            const mobileSearchInput = document.getElementById('mobileSearchInput');

            const handleSearchEvent = (e) => {
                searchQuery = e.target.value.toLowerCase().trim();
                renderCatalog();
            };

            if (searchInput) searchInput.addEventListener('input', handleSearchEvent);
            if (mobileSearchInput) mobileSearchInput.addEventListener('input', handleSearchEvent);
        }

        function handleRouter() {
            const params = new URLSearchParams(window.location.search);
            const productSlug = params.get('product');

            if (productSlug) {
                const product = products.find(p => p.id === productSlug);
                if (product) {
                    renderSingleProductPage(product);
                    return;
                }
            }
            renderCatalogView();
        }

        function renderCatalogView() {
            document.getElementById('pageTitle').textContent = "Budol Finds Hub | Curated Shopee Deals";
            const searchContainer = document.getElementById('searchContainer');
            const mobileSearchContainer = document.getElementById('mobileSearchContainer');
            if (searchContainer) searchContainer.style.display = 'flex';
            if (mobileSearchContainer) mobileSearchContainer.style.display = 'block';

            const main = document.getElementById('mainContent');
            main.innerHTML = `
                <!-- Hero Showcase Banner -->
                <section class="bg-gradient-to-br from-orange-50 via-amber-50/40 to-white py-12 px-4 sm:px-6 lg:px-8 border-b border-slate-200 -mx-4 sm:-mx-6 lg:-mx-8 mb-10">
                    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8 items-center px-4">
                        <div class="space-y-4 text-center md:text-left">
                            <span class="inline-flex items-center gap-1.5 bg-shopee/10 text-shopee px-3 py-1 rounded-full text-xs font-bold uppercase tracking-wider">
                                <i class="fa-solid fa-bolt text-shopee"></i> SEO Sub-Pages Ready for Google Console
                            </span>
                            <h1 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold text-slate-900 tracking-tight leading-tight">
                                Discover the Best <span class="text-shopee">Shopee Budol</span> Finds!
                            </h1>
                            <p class="text-slate-600 text-sm sm:text-base max-w-lg mx-auto md:mx-0">
                                Browse curated aesthetic home essentials, viral tech finds, and daily recommended deals through our trusted affiliate links.
                            </p>
                            <div class="pt-2 flex flex-wrap gap-3 justify-center md:justify-start">
                                <a href="#catalog" class="bg-shopee hover:bg-shopee-dark text-white font-semibold px-6 py-3 rounded-xl shadow-lg shadow-shopee/30 transition hover:-translate-y-0.5">
                                    Browse Catalog <i class="fa-solid fa-arrow-down ml-1 text-xs"></i>
                                </a>
                            </div>
                        </div>
                        <div class="relative flex justify-center">
                            <div class="w-full max-w-md bg-white p-4 rounded-3xl shadow-xl border border-slate-100 relative group overflow-hidden">
                                <div class="absolute top-4 right-4 z-10 bg-shopee text-white text-xs font-bold px-2.5 py-1 rounded-full shadow">
                                    Featured Deal
                                </div>
                                <img src="${products[0] ? products[0].images[0] : ''}" alt="Featured Product" class="w-full h-64 object-cover rounded-2xl group-hover:scale-105 transition duration-500">
                                <div class="mt-4 space-y-2">
                                    <h3 class="font-bold text-slate-900 text-base line-clamp-1">${products[0] ? products[0].title : ''}</h3>
                                    <div class="flex items-center justify-between">
                                        <span class="text-shopee font-extrabold text-lg">₱${products[0] ? products[0].price.toLocaleString() : ''}</span>
                                        <span class="bg-slate-100 text-slate-600 text-xs font-semibold px-2.5 py-1 rounded-lg">Free Shipping</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </section>

                <div id="catalog" class="scroll-mt-20">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-4 mb-8">
                        <div>
                            <h2 class="text-2xl font-bold text-slate-900">Curated Product Catalog</h2>
                            <p class="text-sm text-slate-500">Click any product to open its dedicated sub-page for Google Console indexing.</p>
                        </div>
                        <div class="flex items-center gap-2">
                            <span class="text-xs font-medium text-slate-500">Sort by:</span>
                            <select id="sortSelect" onchange="changeSort(this.value)" class="bg-white border border-slate-300 text-slate-700 text-xs rounded-lg px-3 py-2 focus:outline-none focus:border-shopee">
                                <option value="featured" ${currentSort==='featured'?'selected':''}>Featured / Default</option>
                                <option value="price-low" ${currentSort==='price-low'?'selected':''}>Price: Low to High</option>
                                <option value="price-high" ${currentSort==='price-high'?'selected':''}>Price: High to Low</option>
                                <option value="rating" ${currentSort==='rating'?'selected':''}>Highest Rated</option>
                            </select>
                        </div>
                    </div>

                    <!-- Filter Pills -->
                    <div class="flex items-center gap-2 overflow-x-auto pb-4 mb-6 hide-scrollbar" id="categoryPills">
                        <button onclick="filterCategory('All')" class="category-pill px-4 py-2 rounded-full text-xs sm:text-sm font-semibold whitespace-nowrap ${currentCategory==='All'?'bg-shopee text-white shadow-sm':'bg-white text-slate-600 border border-slate-200 hover:bg-slate-100'} transition">All Products</button>
                        <button onclick="filterCategory('Home Decor')" class="category-pill px-4 py-2 rounded-full text-xs sm:text-sm font-semibold whitespace-nowrap ${currentCategory==='Home Decor'?'bg-shopee text-white shadow-sm':'bg-white text-slate-600 border border-slate-200 hover:bg-slate-100'} transition">Home Decor</button>
                        <button onclick="filterCategory('Tech & Gadgets')" class="category-pill px-4 py-2 rounded-full text-xs sm:text-sm font-semibold whitespace-nowrap ${currentCategory==='Tech & Gadgets'?'bg-shopee text-white shadow-sm':'bg-white text-slate-600 border border-slate-200 hover:bg-slate-100'} transition">Tech & Gadgets</button>
                        <button onclick="filterCategory('Kitchen Essentials')" class="category-pill px-4 py-2 rounded-full text-xs sm:text-sm font-semibold whitespace-nowrap ${currentCategory==='Kitchen Essentials'?'bg-shopee text-white shadow-sm':'bg-white text-slate-600 border border-slate-200 hover:bg-slate-100'} transition">Kitchen Essentials</button>
                        <button onclick="filterCategory('Fashion')" class="category-pill px-4 py-2 rounded-full text-xs sm:text-sm font-semibold whitespace-nowrap ${currentCategory==='Fashion'?'bg-shopee text-white shadow-sm':'bg-white text-slate-600 border border-slate-200 hover:bg-slate-100'} transition">Fashion & Style</button>
                        <button onclick="filterCategory('Beauty & Skincare')" class="category-pill px-4 py-2 rounded-full text-xs sm:text-sm font-semibold whitespace-nowrap ${currentCategory==='Beauty & Skincare'?'bg-shopee text-white shadow-sm':'bg-white text-slate-600 border border-slate-200 hover:bg-slate-100'} transition">Beauty & Skincare</button>
                    </div>

                    <!-- Product Grid -->
                    <div id="productGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6"></div>

                    <!-- Empty State -->
                    <div id="emptyState" class="hidden text-center py-16">
                        <div class="w-16 h-16 bg-slate-100 text-slate-400 rounded-full flex items-center justify-center mx-auto text-2xl mb-4">
                            <i class="fa-solid fa-box-open"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-700">No products found</h3>
                        <p class="text-sm text-slate-500 mt-1">Try adjusting your search query or add products via the admin manager.</p>
                        <button onclick="resetFilters()" class="mt-4 bg-shopee text-white px-4 py-2 rounded-lg text-xs font-semibold shadow hover:bg-shopee-dark transition">Reset All Filters</button>
                    </div>
                </div>
            `;

            renderCatalog();
        }

        function renderCatalog() {
            const grid = document.getElementById('productGrid');
            const emptyState = document.getElementById('emptyState');
            if (!grid) return;

            let filtered = products.map((p, origIndex) => ({ ...p, origIndex })).filter(p => {
                const matchesCat = currentCategory === 'All' || p.category === currentCategory;
                const matchesSearch = (p.title && p.title.toLowerCase().includes(searchQuery)) || (p.category && p.category.toLowerCase().includes(searchQuery));
                return matchesCat && matchesSearch;
            });

            if (currentSort === 'price-low') {
                filtered.sort((a, b) => a.price - b.price);
            } else if (currentSort === 'price-high') {
                filtered.sort((a, b) => b.price - a.price);
            } else if (currentSort === 'rating') {
                filtered.sort((a, b) => (b.rating || 4.8) - (a.rating || 4.8));
            }

            if (filtered.length === 0) {
                grid.innerHTML = '';
                if (emptyState) emptyState.classList.remove('hidden');
                return;
            }

            if (emptyState) emptyState.classList.add('hidden');
            grid.innerHTML = filtered.map(p => {
                const discount = p.originalPrice ? Math.round(((p.originalPrice - p.price) / p.originalPrice) * 100) : 0;
                const images = (p.images && p.images.length > 0) ? p.images : ['https://placehold.co/400x400/eee/666?text=Shopee+Find'];
                const activeImgIdx = activeImageIndices[p.origIndex] || 0;
                const currentImg = images[activeImgIdx] || images[0];
                const altText = p.altText || p.title;
                const subPageUrl = `?product=${p.id}`;

                return `
                    <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl border border-slate-200 overflow-hidden flex flex-col group transition duration-300">
                        <!-- Image Container with Slider -->
                        <div class="relative overflow-hidden aspect-square bg-slate-100">
                            <span class="absolute top-3 left-3 z-10 bg-shopee text-white text-[10px] font-extrabold px-2 py-0.5 rounded-full shadow">
                                ${p.category}
                            </span>
                            ${discount > 0 ? `<span class="absolute top-3 right-3 z-10 bg-amber-500 text-white text-[10px] font-extrabold px-2 py-0.5 rounded-full shadow">-${discount}%</span>` : ''}
                            
                            <a href="${subPageUrl}">
                                <img src="${currentImg}" alt="${altText}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="this.src='https://placehold.co/400x400/eee/666?text=Shopee+Find'">
                            </a>

                            ${images.length > 1 ? `
                                <button onclick="prevCardImage(${p.origIndex}, ${images.length}, event)" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 bg-black/40 hover:bg-black/70 text-white rounded-full flex items-center justify-center text-xs opacity-70 group-hover:opacity-100 transition">
                                    <i class="fa-solid fa-chevron-left"></i>
                                </button>
                                <button onclick="nextCardImage(${p.origIndex}, ${images.length}, event)" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 bg-black/40 hover:bg-black/70 text-white rounded-full flex items-center justify-center text-xs opacity-70 group-hover:opacity-100 transition">
                                    <i class="fa-solid fa-chevron-right"></i>
                                </button>
                            ` : ''}
                        </div>

                        <!-- Thumbnails Row -->
                        ${images.length > 1 ? `
                            <div class="flex items-center gap-1.5 p-2 bg-slate-50 border-t border-slate-100 overflow-x-auto hide-scrollbar">
                                ${images.map((img, idx) => `
                                    <button onclick="switchCardImage(${p.origIndex}, ${idx})" class="w-10 h-10 rounded-lg overflow-hidden flex-shrink-0 border-2 ${idx === activeImgIdx ? 'border-shopee shadow-sm scale-105' : 'border-transparent opacity-70 hover:opacity-100'} transition">
                                        <img src="${img}" class="w-full h-full object-cover" onerror="this.src='https://placehold.co/100x100/eee/666?text=Thumb'">
                                    </button>
                                `).join('')}
                            </div>
                        ` : ''}

                        <div class="p-4 flex flex-col flex-1 justify-between space-y-3">
                            <div>
                                <div class="flex items-center gap-1 text-amber-500 text-xs font-bold mb-1">
                                    <i class="fa-solid fa-star"></i>
                                    <span>${p.rating || 4.8}</span>
                                    <span class="text-slate-400 font-normal">(${p.soldCount || '1k+'} sold)</span>
                                </div>
                                <a href="${subPageUrl}">
                                    <h3 class="font-bold text-slate-800 text-sm line-clamp-2 leading-snug group-hover:text-shopee transition" title="${p.title}">${p.title}</h3>
                                </a>
                            </div>
                            <div class="space-y-2 pt-2 border-t border-slate-100">
                                <div class="flex items-baseline justify-between">
                                    <div>
                                        <span class="text-shopee font-extrabold text-lg">₱${p.price.toLocaleString()}</span>
                                        ${p.originalPrice ? `<span class="text-xs text-slate-400 line-through ml-1">₱${p.originalPrice.toLocaleString()}</span>` : ''}
                                    </div>
                                    <a href="${subPageUrl}" class="text-shopee text-[11px] font-bold hover:underline">
                                        Sub-page <i class="fa-solid fa-arrow-right ml-0.5"></i>
                                    </a>
                                </div>
                                <a href="${p.affLink}" target="_blank" rel="noopener noreferrer" class="w-full bg-shopee hover:bg-shopee-dark text-white font-bold py-2.5 px-4 rounded-xl text-xs flex items-center justify-center gap-2 shadow-md shadow-shopee/20 transition transform active:scale-95">
                                    <i class="fa-solid fa-bag-shopping"></i> Check Price on Shopee
                                </a>
                            </div>
                        </div>
                    </div>
                `;
            }).join('');
        }

        function renderSingleProductPage(p) {
            document.getElementById('pageTitle').textContent = `${p.title} | Budol Finds Hub`;
            const searchContainer = document.getElementById('searchContainer');
            const mobileSearchContainer = document.getElementById('mobileSearchContainer');
            if (searchContainer) searchContainer.style.display = 'none';
            if (mobileSearchContainer) mobileSearchContainer.style.display = 'none';

            const images = (p.images && p.images.length > 0) ? p.images : ['https://placehold.co/400x400/eee/666?text=Shopee+Find'];
            const activeImg = images[singleProductActiveImgIdx] || images[0];
            const discount = p.originalPrice ? Math.round(((p.originalPrice - p.price) / p.originalPrice) * 100) : 0;
            const subPageFullUrl = window.location.href;

            const main = document.getElementById('mainContent');
            main.innerHTML = `
                <div class="max-w-4xl mx-auto space-y-6">
                    <!-- Breadcrumb Navigation -->
                    <div class="flex items-center gap-2 text-xs text-slate-500">
                        <a href="./" class="hover:text-shopee font-medium">Home</a>
                        <i class="fa-solid fa-chevron-right text-[10px]"></i>
                        <span class="font-medium text-slate-700">${p.category}</span>
                        <i class="fa-solid fa-chevron-right text-[10px]"></i>
                        <span class="text-slate-400 truncate max-w-xs">${p.title}</span>
                    </div>

                    <!-- Main Product Card -->
                    <div class="bg-white rounded-3xl shadow-lg border border-slate-200 overflow-hidden grid grid-cols-1 md:grid-cols-2 gap-8 p-6 md:p-8">
                        <!-- Left: Images Gallery -->
                        <div class="space-y-4">
                            <div class="aspect-square bg-slate-100 rounded-2xl overflow-hidden relative shadow-inner">
                                <span class="absolute top-4 left-4 z-10 bg-shopee text-white text-xs font-extrabold px-3 py-1 rounded-full shadow">
                                    ${p.category}
                                </span>
                                ${discount > 0 ? `<span class="absolute top-4 right-4 z-10 bg-amber-500 text-white text-xs font-extrabold px-3 py-1 rounded-full shadow">-${discount}% OFF</span>` : ''}
                                <img src="${activeImg}" alt="${p.altText || p.title}" class="w-full h-full object-cover">
                            </div>

                            <!-- Thumbnails -->
                            ${images.length > 1 ? `
                                <div class="flex items-center gap-2 overflow-x-auto pb-2 hide-scrollbar">
                                    ${images.map((img, idx) => `
                                        <button onclick="switchSingleImage(${idx})" class="w-16 h-16 rounded-xl overflow-hidden flex-shrink-0 border-2 ${idx === singleProductActiveImgIdx ? 'border-shopee shadow-md scale-105' : 'border-slate-200 opacity-70 hover:opacity-100'} transition">
                                            <img src="${img}" class="w-full h-full object-cover">
                                        </button>
                                    `).join('')}
                                </div>
                            ` : ''}
                        </div>

                        <!-- Right: Details & Affiliate Link -->
                        <div class="flex flex-col justify-between space-y-6">
                            <div class="space-y-4">
                                <div class="flex items-center gap-2 text-amber-500 text-sm font-bold">
                                    <i class="fa-solid fa-star"></i>
                                    <span>${p.rating || 4.8}</span>
                                    <span class="text-slate-400 font-normal">(${p.soldCount || '1k+'} sold)</span>
                                </div>
                                <h1 class="text-xl sm:text-2xl font-extrabold text-slate-900 leading-snug">${p.title}</h1>
                                
                                <div class="bg-orange-50/60 p-4 rounded-2xl border border-orange-100 flex items-baseline gap-3">
                                    <span class="text-shopee font-extrabold text-3xl">₱${p.price.toLocaleString()}</span>
                                    ${p.originalPrice ? `<span class="text-sm text-slate-400 line-through">₱${p.originalPrice.toLocaleString()}</span>` : ''}
                                </div>

                                <p class="text-xs text-slate-500 leading-relaxed">
                                    Curated Shopee Budol Find. Verified affiliate recommendation for quality home, tech, and lifestyle essentials. Click below to check current stock and secure vouchers on Shopee.
                                </p>
                            </div>

                            <div class="space-y-3 pt-4 border-t border-slate-100">
                                <a href="${p.affLink}" target="_blank" rel="noopener noreferrer" class="w-full bg-shopee hover:bg-shopee-dark text-white font-bold py-3.5 px-6 rounded-2xl text-sm flex items-center justify-center gap-2 shadow-lg shadow-shopee/30 transition transform active:scale-95">
                                    <i class="fa-solid fa-bag-shopping text-base"></i> Buy & Check Price on Shopee
                                </a>
                                <a href="./" class="w-full bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold py-3 px-6 rounded-2xl text-xs flex items-center justify-center gap-2 transition">
                                    <i class="fa-solid fa-arrow-left"></i> Back to All Catalog Deals
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- SEO Console Indexing Info Box -->
                    <div class="bg-white p-6 rounded-2xl border border-slate-200 text-xs text-slate-500 space-y-2">
                        <h4 class="font-bold text-slate-800 text-sm flex items-center gap-2">
                            <i class="fa-solid fa-globe text-shopee"></i> Google Console Sub-Page URL for Indexing
                        </h4>
                        <p>You can copy this exact sub-page URL and submit it into your Google Search Console URL Inspection tool to index this product independently:</p>
                        <div class="p-2.5 bg-slate-50 font-mono text-slate-700 rounded-lg border border-slate-200 select-all break-all">
                            ${subPageFullUrl}
                        </div>
                    </div>
                </div>
            `;
        }

        function switchSingleImage(idx) {
            singleProductActiveImgIdx = idx;
            const params = new URLSearchParams(window.location.search);
            const productSlug = params.get('product');
            const product = products.find(p => p.id === productSlug);
            if (product) renderSingleProductPage(product);
        }

        function filterCategory(cat) {
            currentCategory = cat;
            renderCatalogView();
        }

        function changeSort(val) {
            currentSort = val;
            renderCatalog();
        }

        function resetFilters() {
            currentCategory = 'All';
            searchQuery = '';
            renderCatalogView();
        }

        function switchCardImage(prodIndex, imgIndex) {
            activeImageIndices[prodIndex] = imgIndex;
            renderCatalog();
        }

        function prevCardImage(prodIndex, totalImages, event) {
            event.stopPropagation();
            let curr = activeImageIndices[prodIndex] || 0;
            curr = (curr - 1 + totalImages) % totalImages;
            activeImageIndices[prodIndex] = curr;
            renderCatalog();
        }

        function nextCardImage(prodIndex, totalImages, event) {
            event.stopPropagation();
            let curr = activeImageIndices[prodIndex] || 0;
            curr = (curr + 1) % totalImages;
            activeImageIndices[prodIndex] = curr;
            renderCatalog();
        }

        // Admin Modal Handlers
        function openAdminModal() {
            document.getElementById('adminModal').classList.remove('hidden');
            renderAdminProductList();
            updateFullCodeField();
        }

        function closeAdminModal() {
            document.getElementById('adminModal').classList.add('hidden');
        }

        function renderAdminProductList() {
            const countEl = document.getElementById('adminProductCount');
            if (countEl) countEl.textContent = products.length;
            const list = document.getElementById('adminProductList');
            if (!list) return;

            list.innerHTML = products.map((p, index) => {
                const thumb = (p.images && p.images.length > 0) ? p.images[0] : 'https://placehold.co/100x100/eee/666?text=Img';
                return `
                    <div class="flex items-center justify-between p-2.5 bg-slate-50 border border-slate-200 rounded-lg text-xs">
                        <div class="flex items-center gap-2.5 truncate">
                            <img src="${thumb}" class="w-9 h-9 object-cover rounded-md flex-shrink-0" onerror="this.src='https://placehold.co/100x100/eee/666?text=Img'">
                            <div class="truncate">
                                <h5 class="font-bold text-slate-800 truncate">${p.title}</h5>
                                <span class="text-slate-500">${p.category} &bull; ?product=${p.id}</span>
                            </div>
                        </div>
                        <button onclick="deleteProduct(${index})" class="bg-red-50 hover:bg-red-100 text-red-600 p-2 rounded-lg transition" title="Delete Product">
                            <i class="fa-solid fa-trash"></i>
                        </button>
                    </div>
                `;
            }).join('');
        }

        function handleAddNewProduct(e) {
            e.preventDefault();
            const title = document.getElementById('newTitle').value.trim();
            const category = document.getElementById('newCategory').value;
            const price = parseFloat(document.getElementById('newPrice').value);
            const originalPrice = parseFloat(document.getElementById('newOriginalPrice').value) || (price * 2);
            const rating = parseFloat(document.getElementById('newRating').value) || 4.9;
            const soldCount = document.getElementById('newSoldCount').value.trim() || "100+";
            const altText = document.getElementById('newAltText').value.trim() || title;
            const rawImages = document.getElementById('newImages').value.trim();
            const affLink = document.getElementById('newAffLink').value.trim();

            let images = rawImages.split(/[\n,;]+/).map(url => url.trim()).filter(url => url.length > 0);
            if (images.length === 0) {
                images = ['https://placehold.co/400x400/eee/666?text=Shopee+Find'];
            }

            const newProd = {
                id: generateSlug(title),
                title,
                category,
                price,
                originalPrice,
                images,
                altText,
                affLink,
                rating,
                soldCount
            };

            products.unshift(newProd);
            saveProductsToStorage();
            handleRouter();
            renderAdminProductList();

            document.getElementById('addProductForm').reset();
            document.getElementById('newRating').value = "4.9";
            document.getElementById('newSoldCount').value = "100+";
            showToast("Product added with category & sub-page!");
        }

        function deleteProduct(index) {
            if (confirm("Are you sure you want to remove this product?")) {
                products.splice(index, 1);
                saveProductsToStorage();
                handleRouter();
                renderAdminProductList();
                showToast("Product deleted successfully.");
            }
        }

        function updateFullCodeField() {
            const output = document.getElementById('fullCodeOutput');
            if (output) {
                let fullHtml = document.documentElement.outerHTML;
                output.value = `<!DOCTYPE html>\n` + fullHtml;
            }
        }

        function copyFullWebsiteCode() {
            updateFullCodeField();
            const textarea = document.getElementById('fullCodeOutput');
            textarea.select();
            textarea.setSelectionRange(0, 999999);
            document.execCommand('copy');
            showToast("Entire website code copied! Paste it directly into your file on GitHub.");
        }

        function showToast(message) {
            const toast = document.getElementById('toast');
            const msg = document.getElementById('toastMessage');
            if (!toast || !msg) return;
            msg.textContent = message;
            toast.classList.remove('translate-y-20', 'opacity-0');
            setTimeout(() => {
                toast.classList.add('translate-y-20', 'opacity-0');
            }, 3500);
        }
    </script>
</body>
</html>
