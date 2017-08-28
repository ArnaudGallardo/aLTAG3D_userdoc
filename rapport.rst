Génération d'un rapport
=======================

La fenêtre de génération de rapport est disponible en cliquant sur le bouton
**Rapport** dans la barre d'outils. Elle permet à l'utilisateur de générer un
rapport d'archivage customisable à l'aide de *templates*.

.. figure:: _static/images/rapport.gif
  :align: center

  Exemple de création d'un rapport

Les *Templates*
---------------

aLTAG3D utilise le moteur de templates **Mustache** dont la documentation est
disponible ici_. N'importe quel template mustache utilisant comme mots-clés les noms
utilisés dans le XSD est donc compatible avec notre système de rapport. Ce
template pourra alors être écrit en LaTeX, HTML, MD, TXT, etc.

.. note::
  Pour plus d'informations concernant la création de templates, veuillez consulter
  la documentation développeur.

.. _ici: https://mustache.github.io/mustache.5.html
