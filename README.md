# Git På Swensko

## Introduktion

Det dagliga språket för de olika kommandona i `git` är på svenska
ett enda stort svengelskakalas. Jag finner mig själv ofta sägandes
_"Kan du pusha branchen?"_ eller _"Jag pullar!"_, vilket känns pinsamt.

Detta dokument ämnar etablera en ren svensk jargong som kan användas
på arbetsplatsen för att med fördel undvika pressade situationer med
kollegor samt boskap.

## Förslag

Nedan följer tabeller över verb och substantiv relaterade till git,
samt förslag på hur vi tillsammans kan bättra oss.

| Engelska      | Svenska       | Engelska      | Svenska       |
|---------------|---------------|---------------|---------------|
| git           | git           | GitHub        | GitHub        |
| pull          | drag          | pull request  | dragförslag   |
| push          | knuffa        | merge         | foga          |
| fetch         | hämta         | checkout      | välj          |
| switch        | byt           | restore       | återställ     |
| amend         | rätta         | cherry-pick   | handplocka    |
| diff          | skillnad      | blame         | klandra       |
| repository    | arkiv         | squash        | mosa          |
| fork          | klyka         | rebase        | ympa          |
| branch (sub.) | gren          | branch (verb) | avgrena       | 
| commit (sub.) | förbindelse   | commit (verb) | förbind       |
| stash (sub.)  | gömma         | stash (verb)  | göm           |
| tag (sub.)    | märkning      | tag (verb)    | märk          |
| master branch | mästergren    | HEAD          | HUVUD         |

## Exempel

    - Kan du dra grenen jag just ympade och knuffa den till GitHub?

    - Jag avgrenade alldeles nyss och förband ändringarna från min gömma där.

    - Skicka ett dragförslag när du är färdig med sammanfogningen!

    - Vi byter till den här grenen och handplockar från mästergrenen.

    - Mosa dina förbindelser innan du sammanfogar.

## Dagligt bruk

Nedan följer en rad kommandoradskommandon för att sätta upp en svensk
gitmiljö. Avsaknaden av svenska tecken i täcknamnen beror på en brist i git
(överväg att förbättra mjukvaran och skicka ett dragförslag!). Följande
kommandon ändrar din `~/.gitconfig` och kommer att verka globalt.

    git config --global alias.drag pull
    git config --global alias.knuffa push
    git config --global alias.foga merge
    git config --global alias.hamta fetch
    git config --global alias.valj checkout
    git config --global alias.byt switch
    git config --global alias.aterstall restore
    git config --global alias.ratta amend
    git config --global alias.handplocka cherry-pick
    git config --global alias.skillnad diff
    git config --global alias.klandra blame
    git config --global alias.mosa squash
    git config --global alias.ympa rebase
    git config --global alias.gren branch
    git config --global alias.forbind commit
    git config --global alias.gom stash
    git config --global alias.mark tag
