# EXO-sur-Wikidata
Excercices à faire sur Wikidata

'''SPARQL
Select DISTINCT ?peinture ?peintureLabel ?lieux ?lieuxLabel
where { ?peinture wdt:P170 wd:Q296. ?peinture wdt:P195 ?lieux.
SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],en".}
} 
'''





