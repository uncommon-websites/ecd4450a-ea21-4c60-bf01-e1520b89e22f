<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Built by Treasury Experts,<br />For Finance Teams
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Bank Connectivity -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Universal Bank Connectivity</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-4">
                        {#each [1, 2, 3, 4, 5, 6] as i}
                            <div class="h-10 w-10 bg-white rounded-full shadow-sm flex items-center justify-center text-gray-400">
                                <div class="h-4 w-4 bg-primary-200 rounded-sm"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Connect to 14,000+ banks globally via real-time APIs, SWIFT, EBICS, or H2H. From JP Morgan to regional banks, all your banking in one place.
                </p>
            </div>

            <!-- TellMe AI Co-pilot -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">TellMe AI Co-pilot</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="h-2 bg-primary-100 rounded w-1/3 mb-4"></div>
                        {#each [1, 2, 3, 4, 5] as i}
                            <div class="flex items-center gap-2">
                                <div class="h-2 w-2 rounded-full bg-primary-200"></div>
                                <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    AI finance co-pilot powered by Google Cloud Vertex AI. Ask questions, predict risks, and automate accounting in natural language.
                </p>
            </div>

            <!-- Expert Implementation -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Expert Implementation</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="flex -space-x-2">
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">A</div>
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">C</div>
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">T</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Dedicated implementation support from former JP Morgan treasury experts who understand your challenges firsthand.
                </p>
            </div>

            <!-- Multi-Currency Support -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">50+ Currencies</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <!-- Currency visualization -->
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm flex items-center justify-center text-[8px]">€</div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm flex items-center justify-center text-[8px]">$</div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm flex items-center justify-center text-[8px]">£</div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-gray-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-primary-600 rounded flex items-center justify-center text-white text-xs">60</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Operate globally with support for 50+ currencies across 60 countries. Real-time FX rates and multi-currency treasury management.
                </p>
            </div>

            <!-- Governance & Permissions -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Governance & Permissions</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold">122</div>
                            <div class="text-[10px] font-bold">2.14</div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-px bg-gray-100 w-full"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-1/2"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-2/3"></div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Granular permission controls, role-based access management, comprehensive audit trails, and customizable governance policies to streamline compliance and safeguard your data.
                </p>
            </div>

            <!-- Modular Platform -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Modular Platform</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as i}
                            <div class={`h-8 w-8 border border-gray-200 ${i === 5 ? 'bg-primary-600 flex items-center justify-center' : 'bg-white'}`}>
                                {#if i === 5}
                                    <div class="h-2 w-2 bg-white rounded-full"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Choose the modules you need: cash management, reconciliation, payments, or full treasury suite. Pricing adapts to your requirements.
                </p>
            </div>
        </div>
    </div>
</section>
