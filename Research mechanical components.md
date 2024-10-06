For the module "wires" we need a terminal block so we can easily take out the wires by hand, thumb for example. we don't want to use any tools loosen a wire  from the box. 

# Research for different models 
There are all kind of models on the market, the output direction is variable, it also differs how many poles are possible per manufacture. For our module we need a terminal block where you can add or remove a wire without a tool. 
The terminal block needs also big enough that the wire is on top of our box so the wire a accessible by the player. The thickness of the wire is also important we don't need a terminal block for above 4mm².

| Manufacture      | Man. Nr.   | Sup. Nr.          | Supplier                                                                                      | Datasheet                                                                                     | output   | Poles |
| ---------------- | ---------- | ----------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | -------- | ----- |
| METZ connect     | AST0450304 | 4849-1366-ND      | [digikey](https://www.digikey.lv/en/products/detail/metz-connect-usa-inc/AST0450604/12178917) | [Datasheet](https://www.metz-connect.com/externalfiles/AST045/905195.PDF)                     | 45°      | 6     |
| Wago corpiration | 2601-3106  | 2946-2601-3106-ND | [digikey](https://www.digikey.sk/en/products/detail/wago-corporation/2601-3106/17121805)      | [Datasheet](https://source.z2data.com/2022/11/30/3/26/12/266816/8038959/WAGO26013106enUS.pdf) | Vertical | 6     |
| Phoenix contact  | 1792261    | 277-9980-ND       | [Digikey](https://www.digikey.sk/en/products/detail/phoenix-contact/1792261/4357179)          | [Datasheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/532/1792261.pdf)     | angled   | 6     |

# Solution for our module
 

|                              | AST0450304      | 2601-3106          | 1792261     |
| ---------------------------- | --------------- | ------------------ | ----------- |
| Poles                        | 6               | 6                  | 6           |
| Mating orientation           | 45°             | 90°                | 45°         |
| connection technology        | spring clamp    | Push-in Cage clamp | spring-cage |
| actuation type               | push to release | lever              | lever       |
| width(6poles) (mm)           | 30              | 22.5               | 46          |
| height (mm)                  | 21.5            | 16.58              | 34.1        |
| wire cross section min (mm²) | 0.2             | 0.14               | 0.2         |
| wire cross section max (mm²) | 1.5             | 1.5                | 6           |

For our module i think the AST0450304 from METZ connect will be the easily accessible because of the push lever on top of this design. We don't need a thick wire so 1.5mm² is more then enough for our application. The dimensions are also within tolerance of the available box. The one issue we can have is that the insert of the cable is not high enough so i would be accessible when the terminal block is placed  trough the top of the box. So the other option will be the 1792261 from Phoenix contact , this one is more robust so i think the insert will be high enough to place it trough the top of the box.
# Retailers AST0450604 Metz connect

| Sup. Nr.    | Supplier                                                                                                                                                              | Datasheet                                                                   | Qty | Price (€) | Total Price (€) | remark                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | --- | --------- | --------------- | ---------------------------- |
| 4849-1366-  | [digikey](https://www.digikey.lv/en/products/detail/metz-connect-usa-inc/AST0450604/12178917)                                                                         | [Datasheet](https://www.metz-connect.com/externalfiles/AST045/905195.PDF)   | 2   | 310,97    | 310.97          | no stock needs to be box 100 |
| AST 045-06  | [Reichelt](https://www.reichelt.com/be/nl/shop/product/veerklem_6-polig_rm5mm_45_-72198)                                                                              | [Datasheet](https://cdn-reichelt.de/documents/datenblatt/C151/AST045.pdf)   | 2   | 1.78      | 3.56            |                              |
| <br>2434487 | [Farnell](https://be.farnell.com/metz-connect/ast0450604/terminal-block-wire-to-brd-6pos/dp/2434487?srsltid=AfmBOopbQueD1pKs1R-_VjtFQbrkQwe4ELfgiLgoMFgO8559-fShHvr1) | [Datasheet](https://media.metz-connect.com/files/171/Data_sheet_AST045.PDF) | 2   | 4.39      | 8.78            |                              |
# Retailers 1792261 Phoenix Contact
| Sup. Nr.    | Supplier                                                                                                                                   | Datasheet                                                                                                                | Qty | Price (€) | Total Price (€) | remark            |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ | --- | --------- | --------------- | ----------------- |
| 277-9980-ND | [Digikey](https://www.digikey.sk/en/products/detail/phoenix-contact/1792261/4357179)                                                       | [Datasheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/532/1792261.pdf)                                | 2   | 12.38     | 24.76           |                   |
| 651-1792261 | [Mouser](https://www.mouser.be/ProductDetail/Phoenix-Contact/1792261?qs=q88POAGIlTEvHpaqmjGA0w%3D%3D)                                      | [Datasheet](https://www.phoenixcontact.com/en-us/products/printed-circuit-board-terminal-pla-5-6-75-zf-1792261?type=pdf) | 2   |           |                 | no stock or price |
| 792-3405    | [RS-online](https://benl.rs-online.com/web/p/pcb-terminal-blocks/7923405?srsltid=AfmBOoqSHfmzrSP40Y53tPCfXXplafQg7Pn3NAdkJtWKxy5n-1--rogS) | [Datasheet](https://docs.rs-online.com/d5f8/0900766b8128b05d.pdf)                                                        | 2   | 13.602    | 17.204          |                   |

