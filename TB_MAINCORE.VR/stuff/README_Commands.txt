### SafeStart
-> Starten - GLOBAL ausf�hren:
	[true] call TB_fnc_safe;
-> Beenden - GLOBAL ausf�hren:
	[false] call TB_fnc_safe;


### ZeusGruppe von der Karte verschwinden (Bluetrack)
-> Ausblenden - LOKAL ausf�hren:
	(group player) setVariable ["ace_map_hideBlueForceMarker", true, true];
-> (Wieder)Einblenden - LOKAL ausf�hren:
	(group player) setVariable ["ace_map_hideBlueForceMarker", false, true];


### GruppenID setzen
-> Person direkt anschauen und davorstehen (Name zwischen den "" �ndern) - LOKAL ausf�hren:
	cursorTarget setGroupIdGlobal ["Alpha"];

