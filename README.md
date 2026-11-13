# Dilli Rush

An open-world crime game set in real central Delhi, playable in the browser.

The street network, building footprints, parks and shop names come from OpenStreetMap
(Connaught Place, Paharganj, Janpath, Kartavya Path, India Gate). Buildings missing from
the map are filled in procedurally along the real streets.

## Run

```sh
python3 -m http.server 8932
# open http://localhost:8932
```

It is a static site: deploy the folder to Vercel as-is (`vercel.json` is included).

## Controls

WASD move, mouse look, click shoot, F enter/exit, Space jump or handbrake, Shift sprint or nitro,
R radio, M map (click to drop a waypoint), T taxi job, Tab controls and cheat codes.

## Credits

- Map data © OpenStreetMap contributors (ODbL)
- Ferrari 458 Italia by vicent091036 (CC BY), Lamborghini Urus by Steven Grey (CC BY-NC),
  Porsche 911 Carrera 4S by Karol Miklas (CC BY-SA)
- Maruti Swift Dzire and Alto 800 by BHP3D, Scorpio by Gouravsuthar (CC BY 4.0), moped by Innerscene (CC0)
- Characters: Quaternius (CC0), three.js examples (Mixamo, Ready Player Me)
- Radio: live public streams (All India Radio, Oye Radio, Radio Panjabi)

The Lamborghini model is licensed non-commercial, so this project is too.
