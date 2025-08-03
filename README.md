<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comment j'ai utilisé ChatGPT pour reprendre le contrôle de ma vie</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#3B82F6',
                        success: '#10B981',
                        danger: '#EF4444'
                    }
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
        .fade-in { animation: fadeIn 0.8s ease-in; }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .slide-in { animation: slideIn 0.6s ease-out; }
        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-30px); }
            to { opacity: 1; transform: translateX(0); }
        }
        /* Custom mobile font sizes */
        @media (max-width: 640px) {
            h1, .h1 { font-size: 2.1rem !important; }
            h2, .h2 { font-size: 1.5rem !important; }
            h3, .h3 { font-size: 1.1rem !important; }
        }
        /* Hide sticky bar on large screens */
        @media (min-width: 768px) {
            .sticky-bar-mobile { display: none !important; }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">

    <!-- Sticky bar mobile -->
    <div class="sticky-bar-mobile fixed bottom-0 left-0 w-full z-40 bg-white border-t border-gray-200 p-3 shadow-lg flex justify-center md:hidden transition-all">
        <button onclick="showPage(4)" class="bg-primary hover:bg-blue-600 text-white font-bold py-3 px-6 rounded-xl text-lg w-full transition-all duration-300">
            🔥 Obtenir le pack complet - 29€
        </button>
    </div>

    <!-- Page 1 - Introduction -->
    <div id="page1" class="page min-h-screen flex items-center justify-center px-4 py-8">
        <div class="max-w-4xl mx-auto text-center fade-in">
            <div class="bg-white rounded-2xl shadow-lg p-8 md:p-12 relative">
                <!-- Offre Urgence -->
                <div class="absolute -top-5 left-1/2 -translate-x-1/2">
                    <div class="bg-danger text-white px-6 py-2 rounded-full shadow font-bold text-sm animate-pulse border-2 border-white">
                        🚨 Offre limitée - Pack à 29€ au lieu de 59€ - Derniers jours !
                    </div>
                </div>
                <div class="mb-10 mt-4">
                    <div class="w-20 h-20 bg-success rounded-full flex items-center justify-center mx-auto mb-6">
                        <span class="text-3xl">🤖</span>
                    </div>
                    <h1 class="text-3xl md:text-5xl font-bold text-gray-900 mb-6 leading-tight h1">
                        Comment j'ai utilisé ChatGPT pour reprendre le contrôle de ma vie, gagner du temps… et générer des revenus
                    </h1>
                </div>
                <div class="bg-gray-50 rounded-xl p-8 mb-8 text-left max-w-2xl mx-auto">
                    <p class="text-lg text-gray-700 mb-4">
                        <strong>Je m'appelle Yannick.</strong><br>
                        Passionné de technologie et d'optimisation, j'ai toujours cherché des moyens d'être plus efficace dans mon quotidien.
                    </p>
                    <p class="text-lg text-gray-700 mb-4">
                        <strong>Quand ChatGPT est arrivé, j'ai tout de suite vu le potentiel.</strong>
                    </p>
                    <p class="text-lg text-gray-700 mb-4">
                        J'ai passé des mois à tester, expérimenter et perfectionner des prompts pour transformer ma façon de travailler, d'apprendre et de créer.
                    </p>
                    <p class="text-lg text-gray-700">
                        Aujourd'hui, je partage mes découvertes les plus puissantes :<br>
                        <strong>5 ebooks concrets, remplis de prompts testés</strong> pour t'aider toi aussi à exploiter le plein potentiel de ChatGPT.
                    </p>
                </div>
                <button onclick="showPage(2)" class="bg-primary hover:bg-blue-600 text-white font-semibold py-4 px-8 rounded-xl text-lg transition-all duration-300 transform hover:scale-105 shadow-lg w-full sm:w-auto">
                    Découvrir les ebooks →
                </button>
            </div>
        </div>
    </div>

    <!-- Page 2 - Présentation des ebooks -->
    <div id="page2" class="page hidden min-h-screen px-4 py-8">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-8 fade-in">
                <h2 class="text-4xl font-bold text-gray-900 mb-3 h2">Mes 5 ebooks ChatGPT</h2>
                <div class="flex items-center justify-center gap-2 mb-2">
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-gray-700 text-lg ml-2">Note 4,9/5 sur 300+ lecteurs</span>
                </div>
                <p class="text-xl text-gray-600">Des guides pratiques avec des prompts testés et approuvés</p>
                <div class="flex items-center justify-center gap-4 mt-3 opacity-70">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Logo-Tiktok-Icon.png" class="h-7" alt="Tiktok"/>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" class="h-7" alt="Insta"/>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" class="h-7" alt="LinkedIn"/>
                    <span class="text-sm">Vu sur</span>
                </div>
            </div>
            <!-- Détails du pack -->
            <div class="bg-white rounded-2xl shadow-lg p-8 mb-8 max-w-4xl mx-auto">
                <div class="text-center mb-8">
                    <h3 class="text-3xl font-bold text-gray-900 mb-4">Pack Complet - 5 Ebooks ChatGPT</h3>
                    <p class="text-lg text-gray-600">Tout ce dont tu as besoin pour maîtriser ChatGPT dans tous les domaines</p>
                </div>
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- Colonne gauche - Contenu détaillé -->
                    <div>
                        <h4 class="text-xl font-bold text-gray-900 mb-4">📚 Ce que contient le pack :</h4>
                        <div class="space-y-5">
                            <!-- Boucle ebooks -->
                            <div class="flex items-start space-x-3">
                                <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center flex-shrink-0">
                                    <span class="text-blue-600 font-bold text-sm">1</span>
                                </div>
                                <div>
                                    <h5 class="font-semibold text-gray-900">Business & Argent</h5>
                                    <p class="text-sm text-gray-600 mb-1">Lancer un business rentable avec ChatGPT</p>
                                    <button onclick="showProductDetails('Business & Argent', 9)" class="text-primary underline text-xs font-bold hover:text-blue-700">Aperçu & acheter seul (9€)</button>
                                </div>
                            </div>
                            <div class="flex items-start space-x-3">
                                <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center flex-shrink-0">
                                    <span class="text-green-600 font-bold text-sm">2</span>
                                </div>
                                <div>
                                    <h5 class="font-semibold text-gray-900">Réseaux Sociaux & Visibilité</h5>
                                    <p class="text-sm text-gray-600 mb-1">Créer du contenu viral sur toutes les plateformes</p>
                                    <button onclick="showProductDetails('Réseaux Sociaux & Visibilité', 9)" class="text-primary underline text-xs font-bold hover:text-blue-700">Aperçu & acheter seul (9€)</button>
                                </div>
                            </div>
                            <div class="flex items-start space-x-3">
                                <div class="w-8 h-8 bg-yellow-100 rounded-full flex items-center justify-center flex-shrink-0">
                                    <span class="text-yellow-600 font-bold text-sm">3</span>
                                </div>
                                <div>
                                    <h5 class="font-semibold text-gray-900">Ventes & Pages de Vente</h5>
                                    <p class="text-sm text-gray-600 mb-1">Rédiger des textes qui convertissent</p>
                                    <button onclick="showProductDetails('Ventes & Pages de Vente', 9)" class="text-primary underline text-xs font-bold hover:text-blue-700">Aperçu & acheter seul (9€)</button>
                                </div>
                            </div>
                            <div class="flex items-start space-x-3">
                                <div class="w-8 h-8 bg-red-100 rounded-full flex items-center justify-center flex-shrink-0">
                                    <span class="text-red-600 font-bold text-sm">4</span>
                                </div>
                                <div>
                                    <h5 class="font-semibold text-gray-900">Création de Contenu & Idées</h5>
                                    <p class="text-sm text-gray-600 mb-1">Ne plus jamais manquer d'inspiration</p>
                                    <button onclick="showProductDetails('Création de Contenu & Idées', 9)" class="text-primary underline text-xs font-bold hover:text-blue-700">Aperçu & acheter seul (9€)</button>
                                </div>
                            </div>
                            <div class="flex items-start space-x-3">
                                <div class="w-8 h-8 bg-purple-100 rounded-full flex items-center justify-center flex-shrink-0">
                                    <span class="text-purple-600 font-bold text-sm">5</span>
                                </div>
                                <div>
                                    <h5 class="font-semibold text-gray-900">Budget & Organisation Familiale</h5>
                                    <p class="text-sm text-gray-600 mb-1">Optimiser sa vie quotidienne et ses finances</p>
                                    <button onclick="showProductDetails('Budget & Organisation Familiale', 9)" class="text-primary underline text-xs font-bold hover:text-blue-700">Aperçu & acheter seul (9€)</button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- Colonne droite - Avantages -->
                    <div>
                        <h4 class="text-xl font-bold text-gray-900 mb-4">🎁 Tes avantages :</h4>
                        <div class="space-y-3">
                            <div class="flex items-center space-x-3"><span class="text-success text-lg">✅</span><span class="text-gray-700">Plus de 200 prompts testés et approuvés</span></div>
                            <div class="flex items-center space-x-3"><span class="text-success text-lg">✅</span><span class="text-gray-700">Accès immédiat par email</span></div>
                            <div class="flex items-center space-x-3"><span class="text-success text-lg">✅</span><span class="text-gray-700">Formats PDF téléchargeables</span></div>
                            <div class="flex items-center space-x-3"><span class="text-success text-lg">✅</span><span class="text-gray-700">Bonus exclusif offert</span></div>
                            <div class="flex items-center space-x-3"><span class="text-success text-lg">✅</span><span class="text-gray-700">Support humain 24h/24</span></div>
                            <div class="flex items-center space-x-3"><span class="text-success text-lg">✅</span><span class="text-gray-700">Mises à jour à vie</span></div>
                            <div class="flex items-center space-x-3"><span class="text-success text-lg">✅</span><span class="text-gray-700">Satisfait ou remboursé 7 jours</span></div>
                        </div>
                        <div class="mt-6 p-4 bg-gradient-to-r from-primary/10 to-success/10 rounded-xl">
                            <div class="flex items-center space-x-2 mb-2">
                                <span class="text-2xl">⚡</span>
                                <span class="font-bold text-gray-900">Résultats rapides</span>
                            </div>
                            <p class="text-sm text-gray-700">Applique les prompts dès aujourd'hui et vois la différence immédiatement !</p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Offre spéciale -->
            <div class="bg-gradient-to-r from-success to-primary rounded-2xl p-8 text-center text-white mb-8">
                <div class="text-4xl mb-4">🎁</div>
                <h3 class="text-2xl font-bold mb-4">Pack Complet Disponible</h3>
                <p class="text-xl mb-4">Les 5 ebooks + 1 bonus offert</p>
                <p class="text-lg mb-6 opacity-90">
                    <strong>Accès immédiat à toute la collection</strong>
                </p>
                <button onclick="showPage(4)" class="bg-white text-primary hover:bg-gray-100 font-bold py-4 px-8 rounded-xl text-lg transition-all duration-300 transform hover:scale-105">
                    Obtenir le pack complet maintenant
                </button>
            </div>
            <!-- FAQ -->
            <div class="bg-white rounded-xl shadow p-6 mt-8 max-w-3xl mx-auto">
                <h4 class="font-bold text-lg mb-3">❓ Foire aux questions</h4>
                <div class="mb-3">
                    <b>Que vais-je recevoir exactement ?</b><br>
                    5 ebooks PDF + 1 bonus, accessibles immédiatement dans ta boîte mail après paiement.
                </div>
                <div class="mb-3">
                    <b>Le paiement est-il sécurisé ?</b><br>
                    Oui, tout passe par PayPal. Tu peux payer par CB, compte PayPal, Google Pay.
                </div>
                <div class="mb-3">
                    <b>Je n’ai jamais utilisé ChatGPT, c’est compliqué ?</b><br>
                    Pas du tout ! Tu as des tutos simples inclus et chaque prompt est “prêt à coller”.
                </div>
                <div class="mb-3">
                    <b>Que se passe-t-il si je ne reçois pas mon ebook ?</b><br>
                    Tu as mon contact direct, je t’envoie tout moi-même sous 24h max !
                </div>
                <div class="mb-3">
                    <b>Je peux acheter un seul ebook ?</b><br>
                    Oui, clique sur “Aperçu & acheter seul” à côté de chaque volume.
                </div>
                <div>
                    <b>Garantie satisfait ou remboursé ?</b><br>
                    Tu as 7 jours pour changer d’avis, sans discuter.
                </div>
            </div>
        </div>
    </div>

    <!-- Page 3 - Témoignages -->
    <div id="page3" class="page hidden min-h-screen px-4 py-8">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-12 fade-in">
                <h2 class="text-4xl font-bold text-gray-900 mb-4 h2">Ce qu'en disent mes lecteurs</h2>
                <p class="text-xl text-gray-600">Des retours authentiques de personnes qui ont appliqué mes conseils</p>
                <div class="flex justify-center gap-2 my-3">
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-yellow-400 text-2xl">★</span>
                    <span class="text-gray-700 ml-2">4,9/5 sur 300+ lecteurs</span>
                </div>
            </div>
            <!-- Témoignages (inchangés, tu peux ajouter des visages ou extraits plus courts) -->
            <!-- ... (utilise tes blocs témoignages actuels) -->
            <!-- ... -->
            <div class="text-center">
                <button onclick="showPage(4)" class="bg-primary hover:bg-blue-600 text-white font-bold py-4 px-8 rounded-xl text-lg transition-all duration-300 transform
