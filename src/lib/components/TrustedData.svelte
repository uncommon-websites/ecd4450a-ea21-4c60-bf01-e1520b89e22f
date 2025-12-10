<script>
    const partners = [
        { name: "JP Morgan", icon: "JP", color: "bg-blue-900" },
        { name: "HSBC", icon: "H", color: "bg-red-600" },
        { name: "Deutsche Bank", icon: "DB", color: "bg-blue-600" },
        { name: "Goldman Sachs", icon: "GS", color: "bg-blue-800" },
        { name: "Citi", icon: "C", color: "bg-blue-500" },
        { name: "Bank of America", icon: "BA", color: "bg-red-700" },
        { name: "SAP", icon: "S", color: "bg-blue-600" },
        { name: "Microsoft Dynamics", icon: "M", color: "bg-blue-500" },
        { name: "Oracle NetSuite", icon: "O", color: "bg-red-600" },
        { name: "Sage", icon: "S", color: "bg-green-600" },
        { name: "Stripe", icon: "S", color: "bg-purple-600" },
        { name: "PayPal", icon: "P", color: "bg-blue-600" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">14,000+ Bank Connections.<br/>Deep ERP Integrations.</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                Connect to any bank globally with real-time API connectivity. Seamlessly integrate with your ERP system for bidirectional data sync. From tier-1 institutions to regional banks, Embat connects your entire financial ecosystem.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
