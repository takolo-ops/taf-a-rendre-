void main() {
  // Déclaration des variables
  double revenuMensuel = 4000.0;
  double loyer = 1200.0;
  double alimentation = 500.0;
  double transport = 200.0;

  // Calcul du total des dépenses
  double totalDepenses = loyer + alimentation + transport;

  // Calcul du solde restant
  double soldeRestant = revenuMensuel - totalDepenses;

  // Vérification du solde
  if (soldeRestant >= 0) {
    print('Vous avez un solde positif de \$${soldeRestant}');
  } else {
    print('Attention ! Votre solde est négatif de \$${soldeRestant.abs()}');
  }
}
# taf-a-rendre-
