# `DCKAP_MultipleCartDelete`
   "Multiple​ ​Cart​ ​Item​ ​Delete"​ ​Magento2​ ​extension​ ​is​ ​used​ ​to​ ​delete​ ​multiple items​ ​from​ ​the shopping​ ​cart​ ​in​ ​a​ ​single​ ​click.​ ​By​ ​default,​ ​Magento​ ​allows​ ​the​ ​buyer to​ ​delete​ ​one​ ​or​ ​all​ ​products​ ​from​ ​the​ ​shopping​ ​cart.
	
But​ ​if​ ​a​ ​user​ ​needs​ ​to​ ​delete​ ​more​ ​than​ ​one​ ​item​ ​without​ ​abandoning​ ​the​ ​cart he/she​ ​has​ ​to​ ​delete​ ​the​ ​item​ ​one​ ​by​ ​one.​ ​On​ ​top​ ​of​ ​this,​ ​the​ ​page​ ​will​ ​also refresh​ ​every​ ​time​ ​the​ ​user​ ​deletes​ ​a​ ​product.​ ​This​ ​is​ ​a​ ​tedious​ ​and​ ​​ ​time-consuming​ ​process. 

This​ ​extension​ ​was​ ​developed​ ​to​ ​resolve​ ​this​ ​exact​ ​pain​ ​point.​ ​With​ ​the “Multiple​ ​Cart​ ​Item​ ​Delete”​ ​Magento2​ ​extension,​ ​buyers​ ​will​ ​have​ ​the​ ​option​ ​to delete​ ​more​ ​than​ ​one​ ​item​ ​from​ ​the shopping​ ​cart​ ​in​ ​a​ ​few​ ​clicks​ ​without refreshing​ ​the​ ​page.
## Version​ ​&​ ​Compatibility​ ​Support
**Version​** : 1.0.0​ ​Stable

**Compatibility​** : CE 2.0.x - 2.3.x; EE 2.0.x - 2.3.x

## Features
- Allows​ ​the​ ​buyer​ ​to​ ​remove​ ​multiple​ ​items​ ​with​ ​a​ ​few​ ​clicks.
- Allows​ ​the​ ​user​ ​to​ ​select​ ​&​ ​delete​ ​all​ ​the​ ​items​ ​in​ ​the​ ​shopping​ ​cart​ ​in​ ​a
 single​ ​click.
- Supports​ ​multiple​ ​store​ ​views.
- Page​ ​will​ ​be​ ​refreshed​ ​only​ ​once​ ​during​ ​the​ ​deletion​ ​process.
- Can​ ​be​ ​used​ ​as​ ​a​ ​developer/testing​ ​tool​ ​(for​ ​removing​ ​multiple​ ​items​ ​in
  cart​ ​while​ ​testing).

## How​ ​to​ ​Install​ ​This​ ​Module?

**Step​ ​1:​** ​ ​Download​ ​the​ ​extension​ ​from​ ​My​ ​Downloadable​ ​Products​ ​in​ ​your
account​ ​from​ ​our​ ​store​ ​or​ ​download​ ​the​ ​package​ ​from​ ​Magento​ ​Marketplace.

**Step​ ​2:​** ​ ​Create​ ​a​ ​directory​ ​​`app\code\DCKAP\MultipleCartDelete`​​ ​in​ ​your
Magento​ ​root​ ​directory​ ​and​ ​unzip​ ​here.

**Step​ ​3:​ ​​** Disable​ ​the​ ​cache​ ​to​ ​avoid​ ​flushing​ ​the​ ​cache,​ ​very​ ​often.​ ​It​ ​may​ ​affect
performance​ ​for​ ​a​ ​while.​ ​However,​ ​you​ ​can​ ​skip​ ​this​ ​step.​ ​If​ ​you​ ​do​ ​so,​ ​clean​ ​the
cache​ ​manually​ ​whenever​ ​needed.
`php​ ​bin/magento​ ​cache:disable`

**Step​ ​4:​** ​ ​Enter​ ​the​ ​following​ ​at​ ​the​ ​command​ ​line​ ​to​ ​enable​ ​the​ ​module.
`php​ ​bin/magento​ ​module:enable​ ​DCKAP_MultipleCartDelete`

**Step​ ​5:​** ​ ​Enter​ ​the​ ​following​ ​at​ ​the​ ​command​ ​line​ ​to​ ​run​ ​the​ ​setup​ ​scripts.
`php​ ​bin/magento​ ​setup:upgrade`

**Step​ ​6:​** ​ ​Enter​ ​the​ ​following​ ​at​ ​the​ ​command​ ​line​ ​if​ ​the​ ​mode​ ​is​ ​set​ ​to​ ​default​ ​or
production​ ​to​ ​deploy​ ​all​ ​the​ ​static​ ​files.
`php​ ​bin/magento​ ​setup:static-content:deploy`

**Step​ ​7:​ ​​** Clear​ ​the​ ​cache​ ​to​ ​configure​ ​the​ ​settings​ ​in​ ​backend​ ​(if​ ​you​ ​skipped
Step3)
`php​ ​bin/magento​ ​cache:clean`

**Step​ ​8:​ ​​** Clear​ ​the​ ​cache​ ​to​ ​apply​ ​all​ ​the​ ​configurations​ ​(if​ ​you​ ​skipped​ ​Step3)
`php​ ​bin/magento​ ​cache:clean`

**Step​ ​9:​ ​​** Enable​ ​the​ ​cache​ ​once​ ​everything​ ​is​ ​done.​ ​Ignore,​ ​if​ ​you​ ​skip​ ​Step3.
`php​ ​bin/magento​ ​cache:enable`

That’s​ ​it.​ ​You​ ​are​ ​done.​ ​If​ ​you​ ​still​ ​face​ ​any​ ​issues​ ​while​ ​installing,​ ​contact​ ​us​ ​at
**extensions@dckap.com**