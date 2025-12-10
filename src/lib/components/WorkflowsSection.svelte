<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Treasury Operations<br />That Run Themselves
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Cash Flow Management -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-primary-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Real-time Cash Position</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-primary-700">
                                <Check size={12} /> <span class="text-gray-600">Syncing banks...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">JP Morgan - €2.4M</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">HSBC - £1.8M</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Deutsche Bank - €950K</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Cash Flow Management</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Real-time visibility across all bank accounts and entities. Monitor cash positions, forecast liquidity, and manage intercompany operations from a single dashboard.
                </p>
            </div>

            <!-- Card 2: AI Reconciliation -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Bank Reconciliation - January 2024</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">AI</div>
                            <span class="text-[10px] text-gray-400">Matched 847 transactions</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Transaction</div>
                                <div class="col-span-2 text-right">Status</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-primary-200 rounded-sm"></div> Payment #1247</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-primary-200 rounded-sm"></div> Invoice #8821</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-primary-200 rounded-sm"></div> Transfer #4512</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded w-1/2 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">AI-Powered Reconciliation</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Automate 90%+ of bank and accounting reconciliation with generative AI. Match transactions, categorize entries, and eliminate manual data entry errors.
                </p>
            </div>

            <!-- Card 3: Payment Automation -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">€</div>
                            <span class="text-[10px] text-gray-500">Payment Approval Flow</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            3 payments pending approval. Total: €45,230
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-500 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Supplier Payment - €15,000</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-500 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Payroll Transfer - €28,450</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Payment Automation</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Execute payments across 50+ currencies with customizable approval workflows. Sequential, joint, or custom rules ensure compliance while maintaining speed.
                </p>
            </div>
        </div>
    </div>
</section>
