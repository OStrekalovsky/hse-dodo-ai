# Пиццерия: Dominos

## [Points for Pizza](https://pointsforpies.dominos.com/)

1. Dominos предложили пользователям бесплатную пиццу за каждые 6 фото пицц. В рамках программы [Points for Pizza](http://phx.corporate-ir.net/phoenix.zhtml?c=135383&p=irol-newsArticle&ID=2385320) пользователи приложения могут каждую неделю отправлять Dominos фото пиццы (пицца может быть какая угодно, даже игрушечная,отметил CEO компаниии) и получать 10 баллов за каждое фото. За 60 баллов Domino's обещают бесплатную пиццу.  
Помимо маркетинговой составляющей акции (подобная акция уже вызвала резонанс в СМИ), этот проект важен с точки зрения сбора информации. Dominos соберут информацию о том, как часто и когда пользователи едят, готовят и покупают пиццу. Это поможет компании усовершенствовать доставку и собственные рестораны, а еще улучшить собственную пиццу.

2. Информации по технологическому стэку этой программы от Dominos найти не удалось, но вот список релевантных материалов:
   1. [Туториал](https://towardsdatascience.com/tensorflow-object-detection-in-videos-avoiding-pizza-donuts-and-cakes-7d188fcb1d2b) по object detection с помощью Tensofrlow Object Detection API
   2. Статьи по SOTA методам в object detection: [Faster R-CNN](https://arxiv.org/abs/1506.01497), [RetinaNet](https://arxiv.org/abs/1708.02002) и [YOLOv3](https://arxiv.org/abs/1804.02767)

3. Путь Dominos в развитии ИИ начался с [Pizza Checker](https://newsroom.dominos.com.au/home/2017/12/27/say-cheese-dominos-new-ai-camera-technology-helps-solve-customers-number-one-frustration), хотя этот проект был отдан на аутсорс. Points for Pizza один из самых новых проектов Dominos, думаю, следующим шагом будет улучшение технологических процессов на основе собранных данных.

# Ресторанный бизнес: Delivery Club

## [Система прогнозирования спроса "Алан"](https://performance360.ru/delivery-club-ii/)

1. Delivery Club [разработали свою систему](https://vc.ru/services/61034-keys-delivery-club-my-sdelali-svoy-ii-kotoryy-prognoziruet-spros-na-dostavku-edy) прогнозирования спроса, распределения заказов и составления расписания курьеров. С помощью системы Алан Delivery Club понимает, когда будет повышенная нагрузка на сервис, а когда можно дать курьерам отдохнуть. Это помогает сделать сервис доставки более надеждным и эффективным.

2. Они используют ансамбль моделей [градиентного бустинга](https://papers.nips.cc/paper/6907-lightgbm-a-highly-efficient-gradient-boosting-decision-tree.pdf), нейросетей и несколько линейных моделей. Озон [делал](https://habr.com/ru/company/ozontech/blog/431950/) похожую штукy. А еще похожей задачей занимался я в Тинькофф банке :)

3. Подобную систему пришлось внедрить, чтобы повысить эффективность доставки: тратить меньше денег и быстрее выполнять заказы, и облегчить человеческий труд. "Алан" -- первый проект компании в области ИИ, сейчас его тестируют на Санкт-Петербурге, скоро будут релизить и на другие города присутствия.

# Производственные компании: TOMRA

## [Система сортировки продуктов TOMRA](https://www.tomra.com/en/sorting/food)

1. TOMRA разработали одноименный продукт, который позволяет сортировать продукты питания оптимально. Например, выбирать какие картофелины пустить на картошку фри (нужны подлиннее), а какие на пюре или чипсы. Это помогает уменьшить количество отходов с производства и увеличить качество конечных продуктов.

2. TOMRA не описывают, какие технологии используют в своих разработках, но на их компанию оформлено много [патентов](https://patents.justia.com/assignee/tomra-systems-asa). Несколько из них про машинное обучение: 1) [Система обнаружения объектов](https://patents.justia.com/patent/9158982), 2) [Оптический девайс](https://patents.justia.com/patent/8126325) для обнаружения объектов. По технической части: скорее всего используют какие-нибудь алгоритмы real time semantic segmentation. SOTA в этой сфере: [BiSeNet](https://arxiv.org/abs/1808.00897v1), [FRRNet](https://arxiv.org/abs/1611.08323v2), [PSPNet](https://arxiv.org/abs/1612.01105v2)

3. Алгоритм стали разрабатывать, когда поняли, сколько можно сэкономить продуктов, если правильно их отбирать для разных нужд. TOMRA - компания, которая занимается только алгоритмом сортировки продуктов, сейчас они обрабатывают всего 11 видов продуктов, в дальнейшем, думаю, они попытаются увеличить это количество, чтобы захватить новые рынки и найти новых клиентов.