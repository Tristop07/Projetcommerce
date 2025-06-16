# Projetcommerce
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projet Final BBB4M - Exportation du Sirop d'Érable</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            scroll-behavior: smooth;
        }
        .navbar {
            transition: all 0.3s ease;
        }
        .navbar.scrolled {
            background-color: rgba(255, 255, 255, 0.95);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .section {
            padding: 4rem 0;
        }
        .table-container {
            overflow-x: auto;
        }
    </style>
</head>
<body class="bg-gray-100">
    <!-- Navigation -->
    <nav id="navbar" class="navbar fixed top-0 w-full bg-white z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="text-xl font-bold">Projet BBB4M 2025</div>
                <div class="space-x-4">
                    <a href="#introduction" class="text-gray-700 hover:text-red-600">Introduction</a>
                    <a href="#development" class="text-gray-700 hover:text-red-600">Développement</a>
                    <a href="#conclusion" class="text-gray-700 hover:text-red-600">Conclusion</a>
                    <a href="#bibliography" class="text-gray-700 hover:text-red-600">Bibliographie</a>
                    <a href="#annexes" class="text-gray-700 hover:text-red-600">Annexes</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="bg-red-600 text-white text-center py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Projet Final – BBB4M – Juin 2025</h1>
            <p class="text-xl mb-6">Exportation du Sirop d'Érable : Une Analyse Stratégique pour le G7</p>
            <p class="text-lg">Par [Votre Nom] | École Secondaire Catholique Sainte-Famille</p>
        </div>
    </section>

    <!-- Introduction -->
    <section id="introduction" class="section bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-6">Introduction</h2>
            <p class="text-lg mb-4">
                En 2025, le Canada préside le sommet du G7 à Kananaskis, Alberta, réunissant les économies avancées pour discuter de défis mondiaux tels que la stabilité économique et le commerce international. Ce projet simule une stratégie d’exportation pour une entreprise canadienne, en sélectionnant le sirop d’érable comme produit à exporter vers trois marchés du G7 : les États-Unis, le Japon et l’Allemagne. À travers un processus de filtrage en trois étapes – critères généraux, techniques et spécifiques – ce rapport identifie le marché le plus prometteur, en intégrant des considérations éthiques et logistiques.
            </p>
            <img src="https://placehold.co/600x400" alt="Sirop d'érable" class="w-full rounded-lg shadow-md my-6">
        </div>
    </section>

    <!-- Development -->
    <section id="development" class="section bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-6">Développement</h2>

            <!-- Product Selection -->
            <div class="mb-8">
                <h3 class="text-2xl font-semibold mb-4">Sélection du produit</h3>
                <p class="text-lg">
                    Le sirop d’érable, produit emblématique du Canada (71 % de la production mondiale), est choisi pour sa valeur culturelle et son potentiel économique. Sa production durable et sa réputation de produit naturel répondent aux attentes des consommateurs internationaux pour des alternatives saines au sucre.
                </p>
            </div>

            <!-- Market Selection -->
            <div class="mb-8">
                <h3 class="text-2xl font-semibold mb-4">Choix des marchés étrangers</h3>
                <p class="text-lg">
                    Trois pays du G7 ont été retenus :
                </p>
                <ul class="list-disc pl-6 text-lg">
                    <li><strong>États-Unis</strong> : 340 millions d’habitants, proximité, ACEUM.</li>
                    <li><strong>Japon</strong> : 125 millions, intérêt pour le naturel, PTPGP.</li>
                    <li><strong>Allemagne</strong> : 84 millions, demande bio, CETA.</li>
                </ul>
            </div>

            <!-- General Criteria -->
            <div class="mb-8">
                <h3 class="text-2xl font-semibold mb-4">Analyse des critères généraux</h3>
                <p class="text-lg mb-4">
                    Les critères évalués incluent la taille du marché, la stabilité politique, les barrières linguistiques et la stabilité monétaire.
                </p>
                <div class="table-container">
                    <table class="w-full text-left border-collapse">
                        <thead>
                            <tr class="bg-gray-200">
                                <th class="p-2">Critères</th>
                                <th class="p-2">États-Unis</th>
                                <th class="p-2">Japon</th>
                                <th class="p-2">Allemagne</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="p-2">Taille (pop./PIB)</td>
                                <td class="p-2">340M / 75k USD</td>
                                <td class="p-2">125M / 45k USD</td>
                                <td class="p-2">84M / 55k USD</td>
                            </tr>
                            <tr>
                                <td class="p-2">Stabilité politique</td>
                                <td class="p-2">4/5</td>
                                <td class="p-2">5/5</td>
                                <td class="p-2">5/5</td>
                            </tr>
                            <tr>
                                <td class="p-2">Barrières linguistiques</td>
                                <td class="p-2">Aucune</td>
                                <td class="p-2">Élevées</td>
                                <td class="p-2">Modérées</td>
                            </tr>
                            <tr>
                                <td class="p-2">Stabilité monétaire</td>
                                <td class="p-2">Stable</td>
                                <td class="p-2">Très stable</td>
                                <td class="p-2">Stable</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Technical Criteria -->
            <div class="mb-8">
                <h3 class="text-2xl font-semibold mb-4">Analyse des critères techniques</h3>
                <p class="text-lg mb-4">
                    Les aspects logistiques et réglementaires incluent :
                </p>
                <ul class="list-disc pl-6 text-lg">
                    <li><strong>États-Unis</strong> : FDA, transport rapide, pas de tarifs (ACEUM).</li>
                    <li><strong>Japon</strong> : JAS complexe, transport maritime, tarifs réduits (PTPGP).</li>
                    <li><strong>Allemagne</strong> : Normes UE, transport maritime, faibles tarifs (CETA).</li>
                </ul>
            </div>

            <!-- Specific Market Analysis -->
            <div class="mb-8">
                <h3 class="text-2xl font-semibold mb-4">Analyse spécifique des marchés</h3>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-4 rounded-lg shadow">
                        <h4 class="text-xl font-semibold mb-2">États-Unis</h4>
                        <p class="text-lg">Populaire avec les pancakes, forte concurrence (Vermont), demande élevée. Marketing : authenticité canadienne.</p>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow">
                        <h4 class="text-xl font-semibold mb-2">Japon</h4>
                        <p class="text-lg">Produit exotique, faible concurrence, demande croissante. Marketing : positionnement luxe.</p>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow">
                        <h4 class="text-xl font-semibold mb-2">Allemagne</h4>
                        <p class="text-lg">Alternative bio, concurrence modérée, intérêt fort. Marketing : certifications bio.</p>
                    </div>
                </div>
            </div>

            <!-- Comparative Table -->
            <div class="mb-8">
                <h3 class="text-2xl font-semibold mb-4">Tableau comparatif</h3>
                <div class="table-container">
                    <table class="w-full text-left border-collapse">
                        <thead>
                            <tr class="bg-gray-200">
                                <th class="p-2">Critères</th>
                                <th class="p-2">Poids</th>
                                <th class="p-2">États-Unis</th>
                                <th class="p-2">Japon</th>
                                <th class="p-2">Allemagne</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="p-2">Taille du marché</td>
                                <td class="p-2">20%</td>
                                <td class="p-2">5</td>
                                <td class="p-2">4</td>
                                <td class="p-2">4</td>
                            </tr>
                            <tr>
                                <td class="p-2">Stabilité politique</td>
                                <td class="p-2">10%</td>
                                <td class="p-2">4</td>
                                <td class="p-2">5</td>
                                <td class="p-2">5</td>
                            </tr>
                            <tr>
                                <td class="p-2">Barrières linguistiques</td>
                                <td class="p-2">5%</td>
                                <td class="p-2">5</td>
                                <td class="p-2">2</td>
                                <td class="p-2">3</td>
                            </tr>
                            <tr>
                                <td class="p-2">Stabilité monétaire</td>
                                <td class="p-2">5%</td>
                                <td class="p-2">4</td>
                                <td class="p-2">5</td>
                                <td class="p-2">5</td>
                            </tr>
                            <tr>
                                <td class="p-2">Réglementations</td>
                                <td class="p-2">15%</td>
                                <td class="p-2">5</td>
                                <td class="p-2">3</td>
                                <td class="p-2">4</td>
                            </tr>
                            <tr>
                                <td class="p-2">Logistique</td>
                                <td class="p-2">15%</td>
                                <td class="p-2">5</td>
                                <td class="p-2">3</td>
                                <td class="p-2">4</td>
                            </tr>
                            <tr>
                                <td class="p-2">Barrières tarifaires</td>
                                <td class="p-2">10%</td>
                                <td class="p-2">5</td>
                                <td class="p-2">4</td>
                                <td class="p-2">4</td>
                            </tr>
                            <tr>
                                <td class="p-2">Culture</td>
                                <td class="p-2">10%</td>
                                <td class="p-2">4</td>
                                <td class="p-2">4</td>
                                <td class="p-2">4</td>
                            </tr>
                            <tr>
                                <td class="p-2">Concurrence</td>
                                <td class="p-2">5%</td>
                                <td class="p-2">3</td>
                                <td class="p-2">4</td>
                                <td class="p-2">4</td>
                            </tr>
                            <tr>
                                <td class="p-2">Demande</td>
                                <td class="p-2">5%</td>
                                <td class="p-2">5</td>
                                <td class="p-2">4</td>
                                <td class="p-2">4</td>
                            </tr>
                            <tr class="font-bold">
                                <td class="p-2">Score total</td>
                                <td class="p-2"></td>
                                <td class="p-2">4.65</td>
                                <td class="p-2">3.65</td>
                                <td class="p-2">4.05</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Final Market Choice -->
            <div class="mb-8">
                <h3 class="text-2xl font-semibold mb-4">Choix du marché final</h3>
                <p class="text-lg">
                    Les États-Unis (score 4.65/5) sont le marché optimal grâce à leur vaste marché, logistique avantageuse, et absence de barrières majeures. Une stratégie de différenciation face à la concurrence locale est nécessaire.
                </p>
            </div>

            <!-- Ethical Considerations -->
            <div>
                <h3 class="text-2xl font-semibold mb-4">Considérations éthiques</h3>
                <ul class="list-disc pl-6 text-lg">
                    <li><strong>Environnement</strong> : Production durable pour limiter l’impact sur les forêts.</li>
                    <li><strong>Concurrence</strong> : Collaboration avec producteurs locaux.</li>
                    <li><strong>Culture</strong> : Respect des traditions dans le marketing.</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Conclusion -->
    <section id="conclusion" class="section bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-6">Conclusion</h2>
            <p class="text-lg">
                Ce projet démontre que les États-Unis sont le marché optimal pour exporter le sirop d’érable, tout en soulignant les défis logistiques, culturels et éthiques du commerce international. Il renforce les compétences analytiques et prépare à des carrières en commerce international.
            </p>
        </div>
    </section>

    <!-- Bibliography -->
    <section id="bibliography" class="section bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-6">Bibliographie</h2>
            <ul class="list-disc pl-6 text-lg">
                <li>Statistique Canada. (2025). <a href="https://www.statcan.gc.ca" class="text-blue-600 hover:underline">Production de sirop d’érable</a>.</li>
                <li>Banque mondiale. (2025). <a href="https://www.worldbank.org" class="text-blue-600 hover:underline">Indicateurs économiques</a>.</li>
                <li>Gouvernement du Canada. (2025). <a href="https://www.international.gc.ca" class="text-blue-600 hover:underline">Accords commerciaux</a>.</li>
            </ul>
        </div>
    </section>

    <!-- Annexes -->
    <section id="annexes" class="section bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-6">Annexes</h2>
            <p class="text-lg mb-4">Contenu visuel supplémentaire :</p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                    <h4 class="text-xl font-semibold mb-2">Graphique : Demande projetée</h4>
                    <img src="https://placehold.co/400x300" alt="Graphique demande" class="w-full rounded-lg shadow">
                </div>
                <div>
                    <h4 class="text-xl font-semibold mb-2">Carte : Routes logistiques</h4>
                    <img src="https://placehold.co/400x300" alt="Carte logistique" class="w-full rounded-lg shadow">
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-6">
        <p>&copy; 2025 [Votre Nom] | École Secondaire Catholique Sainte-Famille</p>
    </footer>

    <!-- JavaScript for Navbar Scroll Effect -->
    <script>
        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });
    </script>
</body>
</html>
