
+++
title = 'Home'
date = 2023-01-01T08:00:00-07:00
draft = false

[heroSection]
  headline = "Esperienza e professionalità al tuo servizio"
  subheadline = "Sistemi riscaldanti a pavimento, Pannelli solari, Installazione di caldaie, Impianti di condizionamento"
  CTA = "Richiedi un preventivo gratuito"
  CTAUrl = "#quote"
  image = "images/home/hero.jpg"
  altText = "Installatore qualificato con clipboard"

  # Optional Stats
  [[heroSection.stats]]
  value = "20+"
  label = "Parti installate al giorno"

  [[heroSection.stats]]
  value = "100+"
  label = "Clienti soddisfatti settimanalmente"

  [[heroSection.stats]]
  value = "10+"
  label = "Nuovi clienti giornalieri"


[textAndImagesSection]
  title = "Garanzia di Qualità"
  headline = "Soluzioni termoidrauliche su richiesta"
  subheadline = "Installiamo i migliori impianti per la tua casa"
  description = """
  La A & B Termoidraulica fornisce impianti di alta qualità con un servizio professionale e cortese.
  """
  
  image = "images/home/feature.jpg"
  imageAlt = "Stretta di mano sopra tubi idraulici"
  image2 = "images/home/feature2.jpg" # optional second image
  image2Alt = "Primo piano degli strumenti idraulici"

  [textAndImagesSection.primaryCTA]
    ctaText = "Chi Siamo"
    ctaUrl = "/about-us"
  [textAndImagesSection.secondaryCTA]
    ctaText = "0344 42173"
    ctaIcon = "phone"
    ctaUrl = "tel:034442173"


[listingSection]
  title = "I nostri servizi"
  headline = "Impianti di riscaldamento e condizionamento 24/7"
  cardType = "simple" 
  section = "services"            
  viewAllText = "Visualizza tutti i servizi"
  viewAllUrl = "/services"

[valuePropositionSection]
  title = "Perché Sceglierci"
  headline = "Perché Siamo i Migliori"
  subheadline = "Qualità, professionalità e cortesia in ogni progetto."

  [[valuePropositionSection.values]]
    icon = "id-card"
    headline = "Tecnici Qualificati"
    subheadline = "Personale con esperienza decennale nel settore."

  [[valuePropositionSection.values]]
    icon = "thumbs-up"
    headline = "Servizio Affidabile"
    subheadline = "Utilizziamo attrezzature e materiali delle marche più prestigiose."

  [[valuePropositionSection.values]]
    icon = "clock"
    headline = "Servizi Puntuali"
    subheadline = "Garantiamo il massimo comfort e il miglior rendimento."

[testimonialSection]
  title = "Testimonianze"
  headline = "Feedback dai nostri clienti"

[quoteSection]
  title = "Per un preventivo gratuito"
  headline = "Richiedi un preventivo"
  subheadline = "Compila il form per ricevere un preventivo personalizzato."

  [quoteSection.form]
    submitText = "Invia"

    [[quoteSection.form.input]]
      name = "Nome"
      placeholder = "Mario"
      required = true
      type = "text"

    [[quoteSection.form.input]]
      name = "Indirizzo email"
      placeholder = "esempio@email.com"
      required = true
      type = "email"

    [[quoteSection.form.input]]
      name = "Messaggio"
      placeholder = "Il tuo messaggio"
      required = true
      type = "textarea"

[menus]
  [menus.main]
    weight = 10
+++
