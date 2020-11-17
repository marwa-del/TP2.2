# TP-02.2
# Répondre à ces questions:

Question 1:

Si vous exécutez l'application de travail à faire avant d'implémenter onSaveInstanceState(), que se passe-t-il si vous faites pivoter le périphérique? Choisissez-en un:

      * Le compteur est réinitialisé à 0, mais le contenu de l'EditText est préservé
      
Question 2:

Quelles méthodes de cycle de vie d'activité sont appelées lorsqu'un changement de configuration de périphérique (tel qu'une rotation) se produit? Choisissez-en un:

      * Android arrête votre activité en appelant onPause(), onStop() et onDestroy(), 
      puis redémarre l'opération en appelant onCreate(), onStart() et onResume().
      
Question 3:

Lorsque dans le cycle de vie de l'activité, onSaveInstanceState() est appelé? Choisissez-en un:

      * onSaveInstanceState() est appelée avant la méthode onStop().
      
Question 4:

Quelles méthodes de cycle de vie d'Activité sont les meilleures à utiliser pour enregistrer des données avant la fin ou la destruction de l'activité? Choisissez-en un:

      * onResume() ou onCreate()
