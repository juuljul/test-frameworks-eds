# test-frameworks-eds

## Description
Utilisation du framework [edspdf](https://github.com/aphp/edspdf) pour tester la détection automatique du layout des PDF. Ajustement du mask-classifier et ajout d'une ligne de code dans le fichier de configuration pour extraire correctement le corps du texte et le style. Visualisation des blocs de texte après installation de la librairie Pillows.


## Installation

1. **Cloner le repository** :
   ```bash
   git clone https://github.com/juuljul/test-frameworks-eds.git
   cd test-frameworks-eds

   python3 -m venv env
   source env/bin/activate  # Sur Windows: env\Scripts\activate
   pip install -r requirements.txt
   ``` 

## Citation

    
    @software{edspdf,
    author  = {Dura, Basile and Wajsburt, Perceval and Calliger, Alice and Gérardin, Christel and Bey, Romain},
    doi     = {10.5281/zenodo.6902977},
    license = {BSD-3-Clause},
    title   = {{EDS-PDF: Smart text extraction from PDF documents}},
    url     = {https://github.com/aphp/edspdf}
    }
    