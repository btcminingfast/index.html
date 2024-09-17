<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bitcoin Mining</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .bg-overlay {
            background-color: rgba(0,0,0,0.7);
            background-blend-mode: overlay;
        }
    </style>
</head>
<body>
    <div class="min-h-screen bg-cover bg-center bg-no-repeat flex flex-col items-center justify-center p-4 md:p-8 bg-overlay" style="background-image: url('https://images.unsplash.com/photo-1605792657660-596af9009e82?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2002&q=80');">
        <h1 class="text-4xl md:text-6xl font-bold text-white mb-8 text-center">Bitcoin Mining</h1>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4 mb-8 w-full max-w-4xl">
            <div class="bg-white bg-opacity-80 backdrop-blur-sm rounded-lg p-4 flex flex-col items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mb-2 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/>
                </svg>
                <h2 class="text-lg font-semibold">Mining Power</h2>
                <p class="text-2xl font-bold">500.0 PH/s</p>
            </div>
            <div class="bg-white bg-opacity-80 backdrop-blur-sm rounded-lg p-4 flex flex-col items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mb-2 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v13m0-13V6a2 2 0 112 2h-2zm0 0V5.5A2.5 2.5 0 109.5 8H12zm-7 4h14M5 12a2 2 0 110-4h14a2 2 0 110 4M5 12v7a2 2 0 002 2h10a2 2 0 002-2v-7"/>
                </svg>
                <h2 class="text-lg font-semibold">Mined Today</h2>
                <p class="text-2xl font-bold">0.05000 BTC</p>
            </div>
            <div class="bg-white bg-opacity-80 backdrop-blur-sm rounded-lg p-4 flex flex-col items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mb-2 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
                </svg>
                <h2 class="text-lg font-semibold">Efficiency</h2>
                <p class="text-2xl font-bold">94%</p>
            </div>
            <div class="bg-white bg-opacity-80 backdrop-blur-sm rounded-lg p-4 flex flex-col items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mb-2 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"/>
                </svg>
                <h2 class="text-lg font-semibold">Active Miners</h2>
                <p class="text-2xl font-bold">1,234,567</p>
            </div>
        </div>
        
        <div class="flex flex-wrap justify-center gap-4 w-full max-w-4xl mb-8">
            <button class="bg-green-600 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">
                Start Mining
            </button>
            <button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                View Statistics
            </button>
            <button class="bg-purple-600 hover:bg-purple-700 text-white font-bold py-2 px-4 rounded">
                Settings
            </button>
        </div>

        <div class="bg-white bg-opacity-80 backdrop-blur-sm rounded-lg p-4 w-full max-w-4xl">
            <h2 class="text-2xl font-bold mb-2 text-center">Total Earnings</h2>
            <p class="text-4xl font-bold text-green-500 text-center">$10,234.56</p>
        </div>
    </div>
</body>
</html>
