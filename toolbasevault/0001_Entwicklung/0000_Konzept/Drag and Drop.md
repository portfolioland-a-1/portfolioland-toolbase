## User Interface - Drag and Drop
Um auf mobilen Endgeräten, sowie Desktops einen möglichst reibungsloses Bedienen zu ermöglichen, nutzen wir das Prinzip des Drag and Drop. Text-Elemente, wie Überschriften, Paragraphen, aber auch Medien-Elemente, wie Bilder und Bewegtbilder können so per Finger/Zeiger-Bewegung einfach kollagiert werden. 
Hierzu gibt [[0001_Designsystem "Portfolioland"|Portfolioland]] ein hilfreiches Raster vor, an dem entlang sich die Elemente anreihen lassen. 
Das Interfacedesign versucht für möglichst viele Einstellungen der Plattform, hier beispielhaft erwähnt: die Anordnung der einzelnen Elemente oder die Anzeigereihenfolge der einzelnen Arbeiten, dieses "haptische" Bedienelement einzusetzen.
# [[Svelte-Grid]]
Svelte-Grid ist eine leistungsstarke Bibliothek, die es ermöglicht, Rasterlayouts in [[0001_Entwicklung/0002_Dependencies/Sveltekit|Sveltekit]]-Anwendungen einfach zu erstellen. Es bietet eine Drag-and-Drop-Funktionalität sowie die Möglichkeit, Elemente innerhalb des Rasters zu vergrößern und zu verkleinern. Diese Funktionen machen es ideal für die Erstellung von benutzerdefinierten Dashboards, interaktiven Design-Oberflächen und anderen Anwendungen, die komplexe Layouts erfordern.

## Datenlayout

```js
/**
* @typedef {Object} Item
* @property {number} x - The x coordinate of the item
* @property {number} y - The y coordinate of the item
* @property {number} w - The width of the item
* @property {number} h - The height of the item
* @property {string} id - The id of the item
* @property {string} content - The content of the item
* @property {string} collectionID - The id of the collection the item belongs to
* @property {string} type - The type of the item
* @property {string} credits - The credits for the item
* @property {string} altTxt - The alt text for the item
*/
/**
* An array of Items 
* @type {Array.<Item>}
*/

let data = [
{
	"x": number,
	"y": number,
	"w": number,
	"h": number,
	"id": id,
	"content": content,
	"collectionID": collectionID,
	"type": "pictures||headlines||paragraphs||...",
	"credits": "",
	"altTxt": ""
	}
];
 ```
 
