# Ft_printf
![illustration printf](./picture.png)
Le projet ft_printf de l'École 42 consiste à recréer la fonction printf du langage C. Cette fonction permet d'afficher des chaînes de caractères formatées et est essentielle en programmation système et développement logiciel. Ce projet développe des compétences avancées en C, notamment la gestion des arguments variables, la manipulation des chaînes de formatage et l’utilisation de fonctions bas niveau comme write.

🏆 Objectifs du Projet
Comprendre le fonctionnement de printf et ses spécificateurs.
Utiliser <stdarg.h> pour gérer un nombre variable d'arguments.
Travailler avec les bases numériques (décimal, hexadécimal, etc.).
Optimiser la gestion de la mémoire et l’affichage de caractères en C.
🛠️ Spécifications Techniques
Fonctionnalités Requises : ft_printf doit gérer les conversions suivantes :

%c → Caractère unique
%s → Chaîne de caractères
%p → Pointeur (adresse mémoire)
%d / %i → Entier signé
%u → Entier non signé
%x / %X → Hexadécimal (minuscule/majuscule)
%% → Affichage du symbole %
Gestion des Paramètres Variables :
Utilisation des macros de <stdarg.h> : va_list, va_start, va_arg et va_end.

Retour de la Fonction :
ft_printf doit retourner le nombre total de caractères affichés, comme la version standard.

🔧 Approche d’Implémentation
Lecture de la Chaîne de Formatage → Identifier les spécificateurs (%).
Gestion Dynamique des Arguments → Utilisation de <stdarg.h>.
Affichage des Caractères avec write → Pas de printf autorisé.
Retour du Nombre de Caractères Affichés → Compteur à incrémenter.

📂 Structure du Projet
ft_printf.c → Fonction principale et parsing des arguments.
ft_printf.h → Prototypes et #include nécessaires.
Fichiers auxiliaires :
ft_putchar_pf.c → Affiche un caractère.
ft_putstr_pf.c → Affiche une chaîne.
ft_putnbr_pf.c → Affiche un entier.
ft_puthex_pf.c → Affiche un nombre en hexadécimal.
ft_putptr_pf.c → Affiche une adresse mémoire.
Makefile → Automatisation de la compilation.

🧪 Tests et Validation
Comparaison avec printf standard.
Tests unitaires pour chaque spécificateur.
Gestion des cas limites : valeurs nulles, chaînes vides, grands nombres, etc.

📚 Ressources Utiles

[📌 Projet ft_printf - Guide GitHub][https://github.com/Tripouille/printfTester]
[📌 Vidéo Explicative sur ft_printf][https://www.youtube.com/watch?v=fbYxk9J3i0k]

🚀 Pourquoi ce projet est important ?
ft_printf permet de développer des compétences clés en C, en apprenant à manipuler des arguments variadiques et en travaillant sur un projet bas niveau essentiel en programmation système et logicielle.

Prêt à relever le défi ? 🔥
