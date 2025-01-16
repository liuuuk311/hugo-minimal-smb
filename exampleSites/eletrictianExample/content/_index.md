
+++
title = 'Home'
date = 2023-01-01T08:00:00-07:00
draft = false

[heroSection]
  headline = "Marco Demontis Impianti Elettrici — Servizi Elettrici"
  subheadline = "Il tuo partner di fiducia per soluzioni elettriche sicure, affidabili ed efficienti."
  CTA = "Richiedi un Preventivo"
  CTAUrl = "#quote"
  image = "images/home/hero.jpg"
  altText = "Un elettricista che lavora su un quadro elettrico"

  # Optional Stats
  [[heroSection.stats]]
  value = "50+"
  label = "Progetti completati settimanalmente"

  [[heroSection.stats]]
  value = "20+"
  label = "Anni di esperienza"

  [[heroSection.stats]]
  value = "100+"
  label = "Clienti soddisfatti mensilmente"


[textAndImagesSection]
  title = "Assicurazione di Qualità"
  headline = "Soluzioni elettriche di cui ti puoi fidare"
  subheadline = "Lavoro elettrico sicuro, affidabile ed efficiente per la tua casa o attività"
  description = """
  Il nostro team di elettricisti certificati fornisce servizi elettrici di altissimo livello, dalle installazioni alle riparazioni d'emergenza. Siamo impegnati a garantire l'alta qualità del lavoro e la sicurezza ed efficienza dei tuoi sistemi elettrici.
  """

  image = "images/home/feature.jpg"
  imageAlt = "Un elettricista che ispeziona un interruttore"
  image2 = "images/home/feature2.jpg" # optional second image
  image2Alt = "Primo piano di utensili e fili elettrici"

  [textAndImagesSection.primaryCTA]
    ctaText = "Chi Siamo"
    ctaUrl = "/about-us"
  [textAndImagesSection.secondaryCTA]
    ctaText = "+39 031 670483"
    ctaIcon = "phone"
    ctaUrl = "tel:+39031670483"


[listingSection]
  title = "I Nostri Servizi"
  headline = "Soluzioni Elettriche Sicure ed Efficienti"
  cardType = "simple" 
  section = "services"            # services/projects or leave blank for CurrentSection
  viewAllText = "Vedi Tutti i Servizi"
  viewAllUrl = "/services"

[valuePropositionSection]
  title = "Perché Sceglierci"
  headline = "Accendiamo la Tua Fiducia"
  subheadline = "Dedicati alla qualità, sicurezza e soddisfazione del cliente."

  [[valuePropositionSection.values]]
    icon = "id-card"
    headline = "Elettricisti Certificati"
    subheadline = "Professionisti formati e certificati su cui puoi contare."

  [[valuePropositionSection.values]]
    icon = "thumbs-up"
    headline = "Servizio di Alta Qualità"
    subheadline = "I nostri clienti si fidano di noi per qualità e affidabilità."

  [[valuePropositionSection.values]]
    icon = "clock"
    headline = "Soluzioni Puntuali"
    subheadline = "Apprezziamo il tuo tempo e garantiamo un servizio puntuale."

[testimonialSection]
  title = "Testimonianze"
  headline = "Cosa Dicono i Nostri Clienti"

[quoteSection]
  title = "Per un preventivo gratuito"
  headline = "Richiedi un preventivo"
  subheadline = "Contattaci oggi stesso per soluzioni elettriche su misura che soddisfano le tue esigenze e superano le tue aspettative."
  
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
