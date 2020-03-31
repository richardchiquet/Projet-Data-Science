# Projet-Data-Science

Dans ce projet nous voulons acquérir les données d'un site "https://osu.ppy.sh/home".

Osu! est un jeu de rythme gratuit pour Windows, Mac OS et Linux (via Mono et Wine), créé par Dean «peppy» Herbert, écrit en C#, et inspiré du jeu Osu! Tatakae! Ōendan (connu en occident sous le nom d'Elite Beat Agents) sur Nintendo DS.
Il a été lancé le 16 septembre 2007 en bêta ouverte.

Comme dans tout jeu de rythme, le joueur doit accomplir des actions en rythme avec la musique. Ici, il s'agit principalement de cliquer sur des disques (osu!), jouer du piano (osu!mania), d'attraper des fruits (osu!catch) ou encore de taper en rythme sur un tambour (osu!taiko).
Une des particularités de ce jeu de rythme est qu'il ne possède pas un nombre limité de morceaux musicaux jouables (appelés des beatmaps dans le jeu). Ce sont les membres de la communauté de joueurs qui créent les beatmaps, dispositions spatio-temporelles des éléments de jeu (disques, fruits, notes de piano et notes du tambour) correspondant à un morceau musical. Elles sont téléchargeables sur le site officiel du jeu.(source Wikipédia)

Dans notre projet nous nous focalisons sur le mode de jeu, Osu!mania. Nous récupérons des musiques et simulons l'appui des touches d'un joueur. Nous devons pour cela lire un fichier, le comprendre et le décoder pour pouvoir indiquer au clavier quand est-ce qu’il doit appuyer. Nous allons aussi analyser tous les appuis d'un joueur lors de ses sessions pour connaitre sa précision et à quel moment il a commis des erreurs.
