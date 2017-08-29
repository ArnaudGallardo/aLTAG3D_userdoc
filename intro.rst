Introduction
============

.. image:: _static/images/altag.jpg
  :align: center

À propos de aLTAG3D
-------------------

aLTAG3D permet de générer des archives de vos projets 3D, compatible avec le
service d'archivage du CINES et du Consortium 3D.

Le fonctionnement d'aLTAG3D cherche à être le plus automatique possible, et donc
à réduire le plus possible le nombre d'informations que vous aurez à remplir manuellement.

aLTAG3D utilise un système de graphes pour permettre un remplissage plus intuitifs
des données d'archivage.

.. _xsd:

À propos du XSD
---------------

Le fichier XSD est un fichier décrivant l'ensemble des informations qui doivent
être contenues dans l'archive exportée par aLTAG3D. C'est donc ce fichier qui détermine
les données demandées par aLTAG3D et la façon dont il les traites. C'est pourquoi
ce fichier doit toujours être à jour, il détermine la structure même du logiciel.

Cependant ne soyez pas inquiet, si votre logiciel utilise un fichier XSD obsolète,
le seul risque est le refus de votre archive par le CINES. Une simple :ref:`mise à jour du XSD <accueil>`
et des données permettra de résoudre ce problème.

.. NOTE::
   La documentation développeur est disponible ici_ !

.. _ici: https://readthedocs.org/projects/altag3d-devdoc/
