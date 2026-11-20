<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>uvp - Moda Contemporánea & Style Store</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f9fafb',
                            100: '#f3f4f6',
                            900: '#111827',
                            accent: '#2563eb',
                            accentHover: '#1d4ed8'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom scrollbar for better visual appeal */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
        .toast-enter {
            transform: translateY(100%);
            opacity: 0;
        }
        .toast-enter-active {
            transform: translateY(0);
            opacity: 1;
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 antialiased font-sans flex flex-col min-h-screen">

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-30 bg-white/90 backdrop-blur-md border-b border-gray-100 transition-all duration-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between gap-4">
            <!-- Brand Logo -->
            <a href="#" onclick="showSection('catalog')" class="flex items-center gap-2 group">
                <span class="bg-gray-900 text-white font-black text-xl tracking-wider px-3 py-1 rounded-lg transition-transform group-hover:scale-105">uvp</span>
                <span class="text-xs uppercase tracking-widest text-gray-500 font-semibold hidden sm:inline">Studio</span>
            </a>

            <!-- Search Bar -->
            <div class="flex-1 max-w-md mx-2 sm:mx-6">
                <div class="relative">
                    <i class="fa-solid fa-magnifying-glass absolute left-3.5 top-1/2 -translate-y-1/2 text-gray-400 text-sm"></i>
                    <input type="text" id="search-input" oninput="handleSearch()" placeholder="Buscar prendas, marcas..." 
                        class="w-full pl-10 pr-4 py-2 bg-gray-100 border border-transparent rounded-full text-sm focus:outline-none focus:bg-white focus:border-gray-300 transition-all">
                </div>
            </div>

            <!-- Header Actions -->
            <div class="flex items-center gap-3">
                <button onclick="toggleCartModal()" class="relative p-2.5 text-gray-700 hover:text-black hover:bg-gray-100 rounded-full transition-all">
                    <i class="fa-solid fa-bag-shopping text-xl"></i>
                    <span id="cart-badge" class="absolute top-1 right-1 bg-blue-600 text-white text-[10px] font-bold w-5 h-5 rounded-full flex items-center justify-center opacity-0 scale-0 transition-all duration-300">0</span>
                </button>
            </div>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8">
        
        <!-- ================= CATALOG SECTION ================= -->
        <section id="catalog-section" class="space-y-8">
            <!-- Hero Banner -->
            <div class="relative rounded-2xl overflow-hidden bg-gray-900 text-white min-h-[280px] sm:min-h-[340px] flex items-center p-8 sm:p-12 shadow-xl">
                <img src="https://images.unsplash.com/photo-1441986300917-64674bd600d8?q=80&w=1200&auto=format&fit=crop" 
                     alt="Banner Moda" 
                     class="absolute inset-0 w-full h-full object-cover opacity-40">
                <div class="relative z-10 max-w-lg space-y-4">
                    <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-md rounded-full text-xs font-semibold uppercase tracking-wider text-white">Nueva Colección 2026</span>
                    <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight">Define tu estilo urbano y minimalista</h1>
                    <p class="text-gray-200 text-sm sm:text-base">Descubre las últimas tendencias en prendas diseñadas para ofrecer confort, elegancia y durabilidad.</p>
                </div>
            </div>

            <!-- Categories / Filter Bar -->
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 border-b border-gray-200 pb-5">
                <div class="flex items-center gap-2 overflow-x-auto pb-2 sm:pb-0 scrollbar-none" id="category-filters">
                    <button onclick="filterCategory('all')" data-cat="all" class="cat-btn bg-gray-900 text-white px-5 py-2 rounded-full text-sm font-medium whitespace-nowrap transition-all shadow-sm">Todos</button>
                    <button onclick="filterCategory('hombre')" data-cat="hombre" class="cat-btn bg-white border border-gray-200 text-gray-700 hover:bg-gray-100 px-5 py-2 rounded-full text-sm font-medium whitespace-nowrap transition-all">Hombre</button>
                    <button onclick="filterCategory('mujer')" data-cat="mujer" class="cat-btn bg-white border border-gray-200 text-gray-700 hover:bg-gray-100 px-5 py-2 rounded-full text-sm font-medium whitespace-nowrap transition-all">Mujer</button>
                    <button onclick="filterCategory('accesorios')" data-cat="accesorios" class="cat-btn bg-white border border-gray-200 text-gray-700 hover:bg-gray-100 px-5 py-2 rounded-full text-sm font-medium whitespace-nowrap transition-all">Accesorios</button>
                    <button onclick="filterCategory('calzado')" data-cat="calzado" class="cat-btn bg-white border border-gray-200 text-gray-700 hover:bg-gray-100 px-5 py-2 rounded-full text-sm font-medium whitespace-nowrap transition-all">Calzado</button>
                </div>
                <div class="text-xs text-gray-500 font-medium self-end sm:self-center">
                    Mostrando <span id="product-count" class="font-bold text-gray-800">0</span> productos
                </div>
            </div>

            <!-- Products Grid -->
            <div id="products-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                <!-- Products dynamically rendered here -->
            </div>

            <!-- Empty State -->
            <div id="empty-state" class="hidden text-center py-16 space-y-3">
                <i class="fa-solid fa-box-open text-5xl text-gray-300"></i>
                <h3 class="text-lg font-semibold text-gray-700">No se encontraron productos</h3>
                <p class="text-sm text-gray-500">Prueba con otra búsqueda o selecciona una categoría diferente.</p>
                <button onclick="resetFilters()" class="inline-block mt-2 px-4 py-2 bg-gray-900 text-white rounded-lg text-sm font-medium">Restablecer filtros</button>
            </div>
        </section>

        <!-- ================= CHECKOUT SECTION ================= -->
        <section id="checkout-section" class="hidden space-y-8 max-w-5xl mx-auto">
            <div class="flex items-center gap-3">
                <button onclick="showSection('catalog')" class="p-2 text-gray-500 hover:text-black rounded-lg hover:bg-gray-100 transition-all">
                    <i class="fa-solid fa-arrow-left text-lg"></i>
                </button>
                <h2 class="text-2xl sm:text-3xl font-bold text-gray-900">Finalizar Compra</h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
                <!-- Checkout Form (Shipping & Payment) -->
                <div class="lg:col-span-7 space-y-6">
                    <form id="checkout-form" onsubmit="processPayment(event)" class="space-y-6">
                        
                        <!-- Shipping Information -->
                        <div class="bg-white p-6 rounded-2xl border border-gray-200 shadow-sm space-y-4">
                            <h3 class="text-lg font-bold text-gray-900 flex items-center gap-2">
                                <i class="fa-solid fa-truck text-blue-600"></i> 1. Información de Envío
                            </h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div class="sm:col-span-2">
                                    <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Nombre Completo</label>
                                    <input type="text" id="cust-name" required placeholder="Ej. Ana García" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                </div>
                                <div class="sm:col-span-2">
                                    <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Correo Electrónico</label>
                                    <input type="email" id="cust-email" required placeholder="tu@email.com" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                </div>
                                <div class="sm:col-span-2">
                                    <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Dirección de Entrega</label>
                                    <input type="text" id="cust-address" required placeholder="Calle 123 #45-67" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Ciudad</label>
                                    <input type="text" id="cust-city" required placeholder="Madrid" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Código Postal</label>
                                    <input type="text" id="cust-zip" required placeholder="28001" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                </div>
                            </div>
                        </div>

                        <!-- Payment Method -->
                        <div class="bg-white p-6 rounded-2xl border border-gray-200 shadow-sm space-y-4">
                            <h3 class="text-lg font-bold text-gray-900 flex items-center gap-2">
                                <i class="fa-solid fa-credit-card text-blue-600"></i> 2. Método de Pago
                            </h3>

                            <!-- Payment Tabs -->
                            <div class="grid grid-cols-2 gap-3">
                                <label class="border-2 border-blue-600 bg-blue-50/50 p-3 rounded-xl cursor-pointer flex items-center justify-center gap-2 text-sm font-semibold text-blue-900">
                                    <input type="radio" name="payment-method" value="card" checked class="text-blue-600 focus:ring-0">
                                    <i class="fa-solid fa-credit-card"></i> Tarjeta
                                </label>
                                <label class="border-2 border-gray-200 p-3 rounded-xl cursor-pointer flex items-center justify-center gap-2 text-sm font-semibold text-gray-600 hover:border-gray-300">
                                    <input type="radio" name="payment-method" value="paypal" disabled class="text-blue-600 focus:ring-0">
                                    <i class="fa-brands fa-paypal"></i> PayPal
                                </label>
                            </div>

                            <!-- Interactive Credit Card Preview -->
                            <div class="relative bg-gradient-to-tr from-gray-900 via-gray-800 to-slate-900 text-white rounded-2xl p-6 shadow-xl space-y-6 overflow-hidden">
                                <div class="flex justify-between items-start">
                                    <i class="fa-solid fa-sim-card text-yellow-400 text-3xl"></i>
                                    <i class="fa-brands fa-cc-visa text-3xl opacity-80" id="card-brand-icon"></i>
                                </div>
                                <div class="space-y-1">
                                    <span class="text-xs uppercase text-gray-400 tracking-wider">Número de Tarjeta</span>
                                    <div id="card-preview-number" class="font-mono text-lg sm:text-xl tracking-widest font-semibold">
                                        •••• •••• •••• ••••
                                    </div>
                                </div>
                                <div class="flex justify-between items-center text-xs">
                                    <div>
                                        <span class="block uppercase text-gray-400 text-[10px]">Titular</span>
                                        <span id="card-preview-holder" class="font-medium uppercase tracking-wider">NOMBRE COMPLETO</span>
                                    </div>
                                    <div>
                                        <span class="block uppercase text-gray-400 text-[10px]">Expira</span>
                                        <span id="card-preview-exp" class="font-mono font-medium">MM/AA</span>
                                    </div>
                                </div>
                            </div>

                            <!-- Card Details Inputs -->
                            <div class="space-y-4">
                                <div>
                                    <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Titular de la Tarjeta</label>
                                    <input type="text" id="card-holder" required placeholder="Como aparece en la tarjeta" oninput="updateCardPreview()" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Número de Tarjeta</label>
                                    <input type="text" id="card-number" required maxlength="19" placeholder="4532 0000 0000 0000" oninput="formatCardNumber(this); updateCardPreview()" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm font-mono focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                </div>
                                <div class="grid grid-cols-2 gap-4">
                                    <div>
                                        <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">Vencimiento</label>
                                        <input type="text" id="card-exp" required maxlength="5" placeholder="MM/AA" oninput="formatExpDate(this); updateCardPreview()" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm font-mono focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-semibold text-gray-600 uppercase mb-1">CVC / CVV</label>
                                        <input type="password" id="card-cvc" required maxlength="4" placeholder="123" class="w-full px-3.5 py-2.5 border border-gray-300 rounded-xl text-sm font-mono focus:ring-2 focus:ring-blue-500 focus:outline-none">
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Submit Button -->
                        <button type="submit" id="pay-button" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 rounded-xl shadow-lg hover:shadow-xl transition-all flex items-center justify-center gap-2 text-base">
                            <i class="fa-solid fa-lock"></i>
                            <span>Pagar <span id="checkout-btn-total">$0.00</span></span>
                        </button>
                    </form>
                </div>

                <!-- Order Summary Side Panel -->
                <div class="lg:col-span-5">
                    <div class="bg-white p-6 rounded-2xl border border-gray-200 shadow-sm sticky top-28 space-y-6">
                        <h3 class="text-lg font-bold text-gray-900 border-b border-gray-100 pb-3">Resumen del Pedido</h3>
                        
                        <!-- Item List Preview -->
                        <div id="checkout-items-list" class="space-y-4 max-h-60 overflow-y-auto pr-1">
                            <!-- Injected dynamically -->
                        </div>

                        <div class="border-t border-gray-100 pt-4 space-y-2 text-sm">
                            <div class="flex justify-between text-gray-600">
                                <span>Subtotal</span>
                                <span id="checkout-subtotal">$0.00</span>
                            </div>
                            <div class="flex justify-between text-gray-600">
                                <span>Envío Estándar</span>
                                <span id="checkout-shipping" class="text-green-600 font-medium">Gratis</span>
                            </div>
                            <div class="flex justify-between text-gray-600">
                                <span>Impuestos (16%)</span>
                                <span id="checkout-tax">$0.00</span>
                            </div>
                            <div class="flex justify-between font-bold text-gray-900 text-lg border-t border-gray-200 pt-3 mt-2">
                                <span>Total</span>
                                <span id="checkout-total" class="text-blue-600">$0.00</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================= CONFIRMATION SECTION / MODAL ================= -->
        <section id="confirmation-section" class="hidden max-w-2xl mx-auto py-12 text-center space-y-6">
            <div class="bg-white p-8 sm:p-12 rounded-3xl border border-gray-100 shadow-xl space-y-6">
                <div class="w-20 h-20 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto text-3xl animate-bounce">
                    <i class="fa-solid fa-check"></i>
                </div>
                <div class="space-y-2">
                    <h2 class="text-3xl font-extrabold text-gray-900">¡Pago Confirmado!</h2>
                    <p class="text-gray-500 text-sm">Gracias por tu compra en uvp Studio. Hemos enviado la confirmación y detalles de seguimiento a tu correo.</p>
                </div>

                <!-- Order Receipt Card -->
                <div class="bg-gray-50 p-6 rounded-2xl text-left border border-gray-200 space-y-3">
                    <div class="flex justify-between items-center text-xs text-gray-500 pb-3 border-b border-gray-200">
                        <span>Nº de Pedido: <strong id="receipt-order-id" class="text-gray-800 font-mono">#000000</strong></span>
                        <span id="receipt-date">--/--/----</span>
                    </div>
                    <div class="space-y-2 text-sm">
                        <div class="flex justify-between">
                            <span class="text-gray-600">Cliente:</span>
                            <span id="receipt-name" class="font-semibold text-gray-800">---</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-gray-600">Dirección:</span>
                            <span id="receipt-address" class="font-semibold text-gray-800">---</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-gray-600">Método de Pago:</span>
                            <span class="font-semibold text-gray-800">Tarjeta (•••• <span id="receipt-card-last4">0000</span>)</span>
                        </div>
                        <div class="flex justify-between font-bold text-base text-gray-900 border-t border-gray-200 pt-2 mt-2">
                            <span>Monto Total:</span>
                            <span id="receipt-total" class="text-blue-600">$0.00</span>
                        </div>
                    </div>
                </div>

                <button onclick="resetStore()" class="px-8 py-3.5 bg-gray-900 hover:bg-black text-white font-bold rounded-xl shadow-md hover:shadow-lg transition-all text-sm">
                    Volver a la Tienda
                </button>
            </div>
        </section>

    </main>

    <!-- ================= SHOPPING CART SIDEBAR ================= -->
    <div id="cart-drawer-overlay" onclick="toggleCartModal()" class="fixed inset-0 bg-black/50 backdrop-blur-sm z-40 hidden transition-opacity duration-300"></div>

    <aside id="cart-drawer" class="fixed top-0 right-0 h-full w-full sm:w-96 bg-white z-50 shadow-2xl transform translate-x-full transition-transform duration-300 ease-in-out flex flex-col">
        <!-- Cart Header -->
        <div class="p-5 border-b border-gray-100 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <i class="fa-solid fa-bag-shopping text-gray-800"></i>
                <h3 class="font-bold text-lg text-gray-900">Tu Carrito</h3>
                <span id="drawer-item-count" class="text-xs bg-gray-100 text-gray-600 font-semibold px-2 py-0.5 rounded-full">0 prendas</span>
            </div>
            <button onclick="toggleCartModal()" class="text-gray-400 hover:text-gray-700 p-1 rounded-lg">
                <i class="fa-solid fa-xmark text-xl"></i>
            </button>
        </div>

        <!-- Cart Items List -->
        <div id="cart-drawer-items" class="flex-1 overflow-y-auto p-5 space-y-4">
            <!-- Dynamic items -->
        </div>

        <!-- Cart Footer / Summary -->
        <div class="p-5 border-t border-gray-100 bg-gray-50 space-y-4">
            <div class="space-y-1.5 text-sm">
                <div class="flex justify-between text-gray-500">
                    <span>Subtotal</span>
                    <span id="cart-subtotal-text" class="font-semibold text-gray-800">$0.00</span>
                </div>
                <div class="flex justify-between text-gray-500 text-xs">
                    <span>Envío e impuestos calculados al checkout</span>
                </div>
            </div>

            <button onclick="proceedToCheckout()" id="cart-checkout-btn" class="w-full bg-gray-900 hover:bg-black text-white font-bold py-3.5 rounded-xl shadow-md transition-all flex items-center justify-center gap-2">
                <span>Ir al Checkout</span>
                <i class="fa-solid fa-arrow-right text-xs"></i>
            </button>
        </div>
    </aside>

    <!-- Toast Notification Container -->
    <div id="toast-container" class="fixed bottom-5 right-5 z-50 space-y-2 pointer-events-none"></div>

    <script>
        // ================= PRODUCT CATALOG DATA =================
        const PRODUCTS = [
            {
                id: 1,
                name: "Chamarra De Cuero Oversize",
                category: "hombre",
                price: 89.99,
                image: "https://images.unsplash.com/photo-1551028719-00167b16eac5?q=80&w=600&auto=format&fit=crop",
                tag: "Bestseller"
            },
            {
                id: 2,
                name: "Playera Básica Algodón Orgánico",
                category: "hombre",
                price: 149,
                image: "https://images.unsplash.com/photo-1521572267360-ee0c2909d518?q=80&w=600&auto=format&fit=crop",
                tag: "Nuevo"
            },
            {
                id: 3,
                name: "Sudadera Beigé Comfort Fit",
                category: "mujer",
                price: 259,
                image: "https://images.unsplash.com/photo-1556905055-8f358a7a47b2?q=80&w=600&auto=format&fit=crop",
                tag: "Tendencia"
            },
            {
                id: 4,
                name: "Abrigo Elegante de Lana",
                category: "mujer",
                price: 135.00,
                image: "https://images.unsplash.com/photo-1539533018447-63fcce2678e3?q=80&w=600&auto=format&fit=crop",
                tag: "Premium"
            },
            {
                id: 5,
                name: "Sneakers Urban Monochrome",
                category: "calzado",
                price: 1200,
                image: "https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?q=80&w=600&auto=format&fit=crop",
                tag: "Exclusivo"
            },
            {
                id: 6,
                name: "Lentes de Sol Marco Negro Classic",
                category: "accesorios",
                price: 59,
                image: "https://images.unsplash.com/photo-1511499767150-a48a237f0083?q=80&w=600&auto=format&fit=crop"
            
            },
            {
                id: 7,
                name: "Jeans Denim Regular Fit",
                category: "hombre",
                price: 1259,
                image: "https://s7d2.scene7.com/is/image/aeo/0111_7594_055_ob?$pdp-mdg-opt$&fmt=webp"
            },
            {
                id: 8,
                name: "Bolso de Mano Minimalista",
                category: "accesorios",
                price: 2100,
                image: "https://images.unsplash.com/photo-1584917865442-de89df76afd3?q=80&w=600&auto=format&fit=crop",
                tag: "Top"
            }
        ];

        // STATE MANAGEMENT
        let cart = [];
        let currentCategory = 'all';
        let searchQuery = '';

        // INITIALIZATION
        window.addEventListener('DOMContentLoaded', () => {
            // Load saved cart from localStorage if exists
            const savedCart = localStorage.getItem('uvp_cart');
            if (savedCart) {
                try {
                    cart = JSON.parse(savedCart);
                } catch (e) {
                    cart = [];
                }
            }
            renderProducts();
            updateCartUI();
        });

        // Save cart to local storage helper
        function saveCart() {
            localStorage.setItem('uvp_cart', JSON.stringify(cart));
        }

        // RENDER PRODUCTS
        function renderProducts() {
            const grid = document.getElementById('products-grid');
            const emptyState = document.getElementById('empty-state');

            // Filter logic
            const filtered = PRODUCTS.filter(product => {
                const matchesCategory = currentCategory === 'all' || product.category === currentCategory;
                const matchesSearch = product.name.toLowerCase().includes(searchQuery.toLowerCase());
                return matchesCategory && matchesSearch;
            });

            document.getElementById('product-count').textContent = filtered.length;

            if (filtered.length === 0) {
                grid.innerHTML = '';
                emptyState.classList.remove('hidden');
                return;
            }

            emptyState.classList.add('hidden');
            grid.innerHTML = filtered.map(product => `
                <div class="group bg-white rounded-2xl border border-gray-100 shadow-sm hover:shadow-xl transition-all duration-300 overflow-hidden flex flex-col justify-between">
                    <div class="relative overflow-hidden bg-gray-100 aspect-square">
                        <img src="${product.image}" alt="${product.name}" 
                             class="w-full h-full object-cover object-center group-hover:scale-105 transition-transform duration-500"
                             loading="lazy">
                        ${product.tag ? `
                            <span class="absolute top-3 left-3 bg-gray-900/80 backdrop-blur-md text-white text-[10px] font-bold uppercase tracking-wider px-2.5 py-1 rounded-full">
                                ${product.tag}
                            </span>
                        ` : ''}
                    </div>

                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-gray-400 uppercase font-semibold tracking-wider">${product.category}</span>
                            <h3 class="font-bold text-gray-900 text-base mt-0.5 line-clamp-1 group-hover:text-blue-600 transition-colors">${product.name}</h3>
                        </div>

                        <div class="flex items-center justify-between pt-2 border-t border-gray-50">
                            <span class="text-xl font-extrabold text-gray-900">$${product.price.toFixed(2)}</span>
                            <button onclick="addToCart(${product.id})" class="bg-gray-900 hover:bg-blue-600 text-white p-3 rounded-xl transition-colors shadow-sm active:scale-95 flex items-center gap-2 text-xs font-semibold">
                                <i class="fa-solid fa-cart-plus text-sm"></i>
                                <span class="hidden sm:inline">Agregar</span>
                            </button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // CATEGORY & SEARCH HANDLERS
        function filterCategory(cat) {
            currentCategory = cat;
            document.querySelectorAll('.cat-btn').forEach(btn => {
                if (btn.dataset.cat === cat) {
                    btn.className = "cat-btn bg-gray-900 text-white px-5 py-2 rounded-full text-sm font-medium whitespace-nowrap transition-all shadow-sm";
                } else {
                    btn.className = "cat-btn bg-white border border-gray-200 text-gray-700 hover:bg-gray-100 px-5 py-2 rounded-full text-sm font-medium whitespace-nowrap transition-all";
                }
            });
            renderProducts();
        }

        function handleSearch() {
            searchQuery = document.getElementById('search-input').value.trim();
            renderProducts();
        }

        function resetFilters() {
            searchQuery = '';
            document.getElementById('search-input').value = '';
            filterCategory('all');
        }

        // CART OPERATIONS
        function addToCart(productId) {
            const product = PRODUCTS.find(p => p.id === productId);
            if (!product) return;

            const existingIndex = cart.findIndex(item => item.id === productId);
            if (existingIndex > -1) {
                cart[existingIndex].quantity += 1;
            } else {
                cart.push({ ...product, quantity: 1 });
            }

            saveCart();
            updateCartUI();
            showToast(`Añadido: ${product.name}`);
        }

        function updateQuantity(productId, change) {
            const index = cart.findIndex(item => item.id === productId);
            if (index > -1) {
                cart[index].quantity += change;
                if (cart[index].quantity <= 0) {
                    cart.splice(index, 1);
                }
            }
            saveCart();
            updateCartUI();
        }

        function removeFromCart(productId) {
            cart = cart.filter(item => item.id !== productId);
            saveCart();
            updateCartUI();
        }

        function getCartTotals() {
            const subtotal = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);
            const tax = subtotal * 0.16; // 16% VAT
            const shipping = subtotal > 100 || subtotal === 0 ? 0 : 10;
            const total = subtotal + tax + shipping;

            return { subtotal, tax, shipping, total };
        }

        // UPDATE CART DISPLAY
        function updateCartUI() {
            const totalItems = cart.reduce((sum, item) => sum + item.quantity, 0);
            const badge = document.getElementById('cart-badge');
            
            // Badge animation
            badge.textContent = totalItems;
            if (totalItems > 0) {
                badge.classList.remove('opacity-0', 'scale-0');
            } else {
                badge.classList.add('opacity-0', 'scale-0');
            }

            document.getElementById('drawer-item-count').textContent = `${totalItems} prendas`;

            // Drawer List Render
            const drawerContainer = document.getElementById('cart-drawer-items');
            if (cart.length === 0) {
                drawerContainer.innerHTML = `
                    <div class="text-center py-12 text-gray-400 space-y-2">
                        <i class="fa-solid fa-bag-shopping text-4xl mb-2"></i>
                        <p class="text-sm font-medium">Tu carrito está vacío</p>
                    </div>
                `;
                document.getElementById('cart-checkout-btn').disabled = true;
                document.getElementById('cart-checkout-btn').classList.add('opacity-50', 'cursor-not-allowed');
            } else {
                document.getElementById('cart-checkout-btn').disabled = false;
                document.getElementById('cart-checkout-btn').classList.remove('opacity-50', 'cursor-not-allowed');

                drawerContainer.innerHTML = cart.map(item => `
                    <div class="flex gap-3 items-center bg-gray-50 p-3 rounded-xl border border-gray-100">
                        <img src="${item.image}" alt="${item.name}" class="w-16 h-16 object-cover rounded-lg">
                        <div class="flex-1 min-w-0">
                            <h4 class="font-bold text-xs text-gray-900 truncate">${item.name}</h4>
                            <span class="text-xs font-bold text-gray-700">$${item.price.toFixed(2)}</span>
                            <div class="flex items-center gap-2 mt-2">
                                <div class="flex items-center border border-gray-300 rounded-lg bg-white">
                                    <button onclick="updateQuantity(${item.id}, -1)" class="px-2 py-0.5 text-xs text-gray-600 hover:bg-gray-100 rounded-l-lg">-</button>
                                    <span class="px-2 text-xs font-semibold">${item.quantity}</span>
                                    <button onclick="updateQuantity(${item.id}, 1)" class="px-2 py-0.5 text-xs text-gray-600 hover:bg-gray-100 rounded-r-lg">+</button>
                                </div>
                            </div>
                        </div>
                        <button onclick="removeFromCart(${item.id})" class="text-gray-400 hover:text-red-500 p-2">
                            <i class="fa-solid fa-trash-can text-sm"></i>
                        </button>
                    </div>
                `).join('');
            }

            const { subtotal } = getCartTotals();
            document.getElementById('cart-subtotal-text').textContent = `$${subtotal.toFixed(2)}`;

            // Render Checkout Summary if on Checkout
            renderCheckoutSummary();
        }

        // CART DRAWER TOGGLE
        function toggleCartModal() {
            const drawer = document.getElementById('cart-drawer');
            const overlay = document.getElementById('cart-drawer-overlay');
            const isOpen = !drawer.classList.contains('translate-x-full');

            if (isOpen) {
                drawer.classList.add('translate-x-full');
                overlay.classList.add('hidden');
            } else {
                drawer.classList.remove('translate-x-full');
                overlay.classList.remove('hidden');
            }
        }

        // NAVIGATION BETWEEN VIEWS
        function showSection(sectionName) {
            document.getElementById('catalog-section').classList.add('hidden');
            document.getElementById('checkout-section').classList.add('hidden');
            document.getElementById('confirmation-section').classList.add('hidden');

            if (sectionName === 'catalog') {
                document.getElementById('catalog-section').classList.remove('hidden');
            } else if (sectionName === 'checkout') {
                document.getElementById('checkout-section').classList.remove('hidden');
            } else if (sectionName === 'confirmation') {
                document.getElementById('confirmation-section').classList.remove('hidden');
            }

            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function proceedToCheckout() {
            if (cart.length === 0) return;
            toggleCartModal();
            renderCheckoutSummary();
            showSection('checkout');
        }

        // CHECKOUT SUMMARY RENDER
        function renderCheckoutSummary() {
            const checkoutList = document.getElementById('checkout-items-list');
            const { subtotal, tax, shipping, total } = getCartTotals();

            checkoutList.innerHTML = cart.map(item => `
                <div class="flex justify-between items-center text-sm">
                    <div class="flex items-center gap-3">
                        <img src="${item.image}" class="w-10 h-10 object-cover rounded-md">
                        <div>
                            <p class="font-semibold text-gray-800 text-xs">${item.name}</p>
                            <span class="text-xs text-gray-400">Cant: ${item.quantity}</span>
                        </div>
                    </div>
                    <span class="font-semibold text-gray-700">$${(item.price * item.quantity).toFixed(2)}</span>
                </div>
            `).join('');

            document.getElementById('checkout-subtotal').textContent = `$${subtotal.toFixed(2)}`;
            document.getElementById('checkout-tax').textContent = `$${tax.toFixed(2)}`;
            document.getElementById('checkout-shipping').textContent = shipping === 0 ? 'Gratis' : `$${shipping.toFixed(2)}`;
            document.getElementById('checkout-total').textContent = `$${total.toFixed(2)}`;
            document.getElementById('checkout-btn-total').textContent = `$${total.toFixed(2)}`;
        }

        // CREDIT CARD INTERACTION AND FORMATTING
        function formatCardNumber(input) {
            let value = input.value.replace(/\D/g, '');
            value = value.substring(0, 16);
            let formatted = value.match(/.{1,4}/g)?.join(' ') || value;
            input.value = formatted;
        }

        function formatExpDate(input) {
            let value = input.value.replace(/\D/g, '');
            if (value.length >= 2) {
                value = value.substring(0, 2) + '/' + value.substring(2, 4);
            }
            input.value = value;
        }

        function updateCardPreview() {
            const number = document.getElementById('card-number').value;
            const holder = document.getElementById('card-holder').value;
            const exp = document.getElementById('card-exp').value;

            document.getElementById('card-preview-number').textContent = number || '•••• •••• •••• ••••';
            document.getElementById('card-preview-holder').textContent = holder ? holder.toUpperCase() : 'NOMBRE COMPLETO';
            document.getElementById('card-preview-exp').textContent = exp || 'MM/AA';

            // Simple Brand Icon Detection
            const brandIcon = document.getElementById('card-brand-icon');
            if (number.startsWith('4')) {
                brandIcon.className = "fa-brands fa-cc-visa text-3xl text-white";
            } else if (number.startsWith('5')) {
                brandIcon.className = "fa-brands fa-cc-mastercard text-3xl text-white";
            } else {
                brandIcon.className = "fa-solid fa-credit-card text-3xl text-white opacity-80";
            }
        }

        // PROCESS PAYMENT SIMULATION
        function processPayment(event) {
            event.preventDefault();

            const payBtn = document.getElementById('pay-button');
            const originalContent = payBtn.innerHTML;

            // Loading state
            payBtn.disabled = true;
            payBtn.innerHTML = `<i class="fa-solid fa-spinner animate-spin text-lg"></i> Procesando Pago...`;

            setTimeout(() => {
                const { total } = getCartTotals();
                const name = document.getElementById('cust-name').value;
                const address = document.getElementById('cust-address').value;
                const city = document.getElementById('cust-city').value;
                const cardNum = document.getElementById('card-number').value;
                const last4 = cardNum.slice(-4) || '4242';

                // Fill receipt values
                document.getElementById('receipt-order-id').textContent = '#' + Math.floor(100000 + Math.random() * 900000);
                document.getElementById('receipt-date').textContent = new Date().toLocaleDateString('es-ES');
                document.getElementById('receipt-name').textContent = name;
                document.getElementById('receipt-address').textContent = `${address}, ${city}`;
                document.getElementById('receipt-card-last4').textContent = last4;
                document.getElementById('receipt-total').textContent = `$${total.toFixed(2)}`;

                // Clear cart and show confirmation
                cart = [];
                saveCart();
                updateCartUI();

                payBtn.disabled = false;
                payBtn.innerHTML = originalContent;

                showSection('confirmation');
            }, 1800);
        }

        function resetStore() {
            document.getElementById('checkout-form').reset();
            updateCardPreview();
            showSection('catalog');
        }

        // TOAST NOTIFICATIONS
        function showToast(message) {
            const container = document.getElementById('toast-container');
            const toast = document.createElement('div');
            toast.className = 'bg-gray-900 text-white text-xs font-semibold px-4 py-3 rounded-xl shadow-xl flex items-center gap-2 transform transition-all duration-300 pointer-events-auto';
            toast.innerHTML = `<i class="fa-solid fa-circle-check text-green-400"></i> <span>${message}</span>`;
            
            container.appendChild(toast);

            setTimeout(() => {
                toast.classList.add('opacity-0', 'translate-y-2');
                setTimeout(() => toast.remove(), 300);
            }, 2500);
        }
    </script>
</body>
</html>
