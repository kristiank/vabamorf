Kasutamine
----------
etsyn k�ivitamine ilma parameetriteta kuvab k�sureaparameetrid koos seletusega.

Sisendfail
----------
Kodeering: UTF8, ilma BOM-ita
Struktuur:
{
	words: [
		{
			"lemma": "string",
			"partofspeech": "string",
			"form": "string",
			"hint": "string"
		},
		...
	]
}
hint ja partofspeech v�ivad puududa.

V�ljundfail
-----------
Kodeering: UTF8, ilma BOM-ita
S�nadele (words[*]) lisatakse t�iendav informatsioon. 
"text": [ "string", ... ]
