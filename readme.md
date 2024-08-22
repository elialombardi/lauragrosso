hugo -D -d docs
hugo server -D --disableFastRender
hugo mod clean


new:
ti ho invitato al repository
su github
per lanciare il sito in locale:
hugo server -D --disableFastRender
invece quando vuoi pubblicarlo prima lanci:
hugo -D -d docs

e poi fai commit e push delle modifiche
tutto ciò che sta nella cartella docs non va toccato, 
perché viene poi sovrascritto quando lanci hugo -D -d docs
