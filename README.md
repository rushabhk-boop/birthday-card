# Birthday card

An animated birthday card in three acts. A sealed envelope opens into a tri-fold scrapbook card with eight hidden surprises. Then the lights go out: her name appears in the stars, the moon from the night she was born, live counters of her life so far, candles she blows out into the microphone, sky lanterns and a birthday selfie. Finally she is summoned to the Court of Birthdays: charges, an Objection! button, a viva on Latin maxims, a gavel judgment and a birthday constitution she signs with her finger.

## Make a card

Open `make.html` on the site, fill in the form and send the link it gives you.

Nothing personal is stored in this repo. The name, date of birth, sender and message live only in the link, after the `#`:

```
https://<user>.github.io/birthday-card/#to=Priya&born=2000-11-02&from=Rushabh&msg=Your+message
```

If her birthday is still to come this year, the card shows a countdown until midnight on the day ("Open it anyway" skips it).

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000/. The microphone and camera need `localhost` or HTTPS.
