---
date: '2025-11-11'
draft: false
title: 'Unity "дорожает"'
ShowToc: false
tags: ["новости", "Unity", "перевод"]
cover:
  image: images/covers/unity.png
---

На днях многие разработчики на юнити получили на почту письмо о повышении цен на юнити, но - эта новость не такая уж и плохая, чем она кажется после Runtime Fee и других их ошибок. Давайте разбираться!

Вот такое письмо пришло разработчикам (Спасибо [GameFromScratch](https://gamefromscratch.com/unity-announce-price-increases-3/)):

> Hi,  
> 
> We will be making adjustments to Unity pricing and packaging in line with last year’s commitment to predictable, annual price adjustments.  
> 
> Unity Pro and Enterprise will see a 5% price increase, starting January 12th. Unity Pro and Enterprise plans on 6.3 LTS will no longer include Havok Physics for Unity. Later in 2026, all plans will gain expanded free access to Unity DevOps functionality.  
> 
> **Key facts:**  
> Unity Pro and Enterprise: If you’re an existing subscriber, your price will update at your next renewal on or after Jan 12, 2026. Final amounts may vary by region due to local taxes, currency, and rounding, and will be shown at checkout or in your quote.  
> 
> Unity DevOps: We’re removing seat charges for Unity Version Control hosted in our public cloud. We’re expanding the free tier of cloud pay-as-you-go features to 25 GB of storage (up from 5 GB), adding 100 Mac build minutes for Unity Build Automation, and 100 GB of free egress. See more information [here](http://url3090.unity3d.com/ls/click?upn=u001.y5Ti9zxf3DkWkwuRwmVrWYO50PgzGeBXygTYKR-2FPl1OXhy1h-2BEFolwErZKHb1EF-2FGKH1o88ItKPfz-2Bo-2F3grou1M0NDJFAbSV3K4beCykECU-3DQ_ar_OT90f1wv-2FrQdCTyL4-2Fqp-2B5dwG85HCL9TgqsZaI98ZAc9GZLz8ckVicYyVPBFP-2BuG5yw7yH5Oqm7Z-2F7e6KVAzANSlj2e-2FoITl4bohg7-2ByP3cM1LJHAcXxnfX2klFutp4ptXasW2QIVNuqMSidtLhCAzth67xjeK8SU35gRsfFUxx6c-2FN4iMZ-2BL0nYdG2vFaYoFXMTyj7S6ryFiTgki8Pa-2FexZSQMF7rqLvSholf8VRzqSUk9RlE4Ur1kKU16OgbmnUzumvxbyl0vsXlMGoldtE6bOdDrJ9lfpsgyIVASwtERUY3QRADUrXndmZkyW-2FeXb5dgTP3-2FadLRGmWJTM542kLeWw0fN4SSkZ12-2B0E7b2hbiYiOAcYoZvRlHU-2BbBHlFw2o9vQiICQ-2Bt73DsI9p3sDnnFo-2BWcCSeZWyJDJ1xAH5Bn-2F4u6tT-2Fl2aUVx-2FVn5Y-2FbXLvqJGOsQCbsxxf9JvNu07zoTTqvs38Qn-2FdqgWKEW15SakEfnpS0dK0Ak-2BkelqhST9XouXGGxsDe4r3VG48UfOXEn8mPJkho0YAd9UZHYFflOOcam-2BWE4pXgoIxZjkSQdUmwZKbjLWT5lxK3PQVNN2T1eG0bLkL0cL6LgC1g13OdYncFh9RhfY0CizmO7bNkBFYvugiKUKxWJ-2BCU2088mGee26xQkaOk0rPAg6J3NG2BwvIoM0r15EHqhA8I-2FIojbkKLbAfOSx3-2B9xcEvyqC0-2FBeBuTMhb9Ij6wd0tyeD-2FJ9d0kBU5lqafHlyEHPVHCbXrK8ItRDMGUwfHgsZ2s-2Fa4A9esb92HfWmDfSWJcXKRqReXH8yQNvyImEioyNCOa3er4tuDAtKx7VR-2BR3xzio4Yf0m81vkv0llm74B5UKcF6FHOvoPQ1D2YYit9wwyGg3eBwF-2BsoF96a32vIP0PgVQ3zeGG3AMmo6kf5cEmY89fdhZxOMp8AbtgmvZSS-2BPq7HdAm7RFTgXigrsFstZwtIAjdxreuBkwJnttXu99sfc-2BbmyT5EdxcpNOrJ-2B0P43x3HdqczOPUrPPu36-2FSMC3xE8Kk-2BKupELk3jUqn1n-2FxBYxVwKkxf2QdUDfBuPqHLyIz7Z9QifmYVQishDsrnaiKnWCOAB3dVbwQqK5uSVBGHHFA-3D).  
> 
> Havok Physics for Unity: Starting with Unity 6.3, Havok Physics will no longer be included with Pro or Enterprise. Havok Physics for Unity remains supported for the remainder of Unity 2022 LTS and Unity 6.0 LTS. See more information [here](http://url3090.unity3d.com/ls/click?upn=u001.y5Ti9zxf3DkWkwuRwmVrWYO50PgzGeBXygTYKR-2FPl1OXhy1h-2BEFolwErZKHb1EF-2FBuXFsQq3Y2U-2Fw-2FdpokbJyw-3D-3DlOil_OT90f1wv-2FrQdCTyL4-2Fqp-2B5dwG85HCL9TgqsZaI98ZAc9GZLz8ckVicYyVPBFP-2BuG5yw7yH5Oqm7Z-2F7e6KVAzANSlj2e-2FoITl4bohg7-2ByP3cM1LJHAcXxnfX2klFutp4ptXasW2QIVNuqMSidtLhCAzth67xjeK8SU35gRsfFUxx6c-2FN4iMZ-2BL0nYdG2vFaYoFXMTyj7S6ryFiTgki8Pa-2FexZSQMF7rqLvSholf8VRzqSUk9RlE4Ur1kKU16OgbmnUzumvxbyl0vsXlMGoldtE6bOdDrJ9lfpsgyIVASwtERUY3QRADUrXndmZkyW-2FeXb5dgTP3-2FadLRGmWJTM542kLeWw0fN4SSkZ12-2B0E7b2hbiYiOAcYoZvRlHU-2BbBHlFw2o9vQiICQ-2Bt73DsI9p3sDnnFo-2BWcCSeZWyJDJ1xAH5Bn-2F4u6tT-2Fl2aUVx-2FVn5Y-2FbXLvqJGOsQCbsxxf9JvNu07zoTTqvs38Qn-2FdqgWKEW15SakEfnpS0dK0Ak-2BkelqhST9XouXGGxsDe4r3VG48UfOXEn8mPJkho0YAd9UZHYFflOOcam-2BWE4pXgoIxZjkSQdUmwZKbjLWT5lxK3PQVNN2T1eG0bLkL0cL6LgC1g13OdYncFh9RhfY0CizmO7bNkBFYvugiKUKxWJ-2BCU2088mGee26xQkaOk0rPAg6J3NG2BwvIoM0r15EHqhA8I-2FIojbkKLbAfOSx3-2B9xcEvyqC0-2FBeBuTMhb9Ij6wd0tyeD-2FJ9d0kBU5lqafHlyEHPVHCbXrK8ItRDMGUwfHgsZ2s-2Fa4A9esb92HfWmDfSWJcXKRqReXH8yQNvyImEioyNCOa3er4tuDAtKx7VR-2BR3xzio4Yf0m81vkv0llm74B5UKcF6FHOvoPQ1D2YYit9wwyGg3eBwF-2BsoF96a32vIP0PgVQ3zeGG3AMmo6kf5cEmY89fc0WG8W1wcM9ktMHBpUtiW81aXszcL8rqFd04UjyfNOPhV254hI1gGojuZpILpQXGwV18fuQcF2yGbar48W5Mxcgcgj0PrxnFhmx0hT2BpS9pUD5Ozkymfa-2B1i1xEbPq3z3-2FhkLWq3bodXqNPNS4R7y65ZJkRIuDgkxDttrIvUkDlDXTYQSUuUKabgoPek9brM-3D).  
> 
> Learn more about these changes and what they mean for you on our [pricing updates page.](http://url3090.unity3d.com/ls/click?upn=u001.y5Ti9zxf3DkWkwuRwmVrWYO50PgzGeBXygTYKR-2FPl1OXhy1h-2BEFolwErZKHb1EF-2Fpho8mosGI2OCp4qQQh-2FLKQ-3D-3D2i8M_OT90f1wv-2FrQdCTyL4-2Fqp-2B5dwG85HCL9TgqsZaI98ZAc9GZLz8ckVicYyVPBFP-2BuG5yw7yH5Oqm7Z-2F7e6KVAzANSlj2e-2FoITl4bohg7-2ByP3cM1LJHAcXxnfX2klFutp4ptXasW2QIVNuqMSidtLhCAzth67xjeK8SU35gRsfFUxx6c-2FN4iMZ-2BL0nYdG2vFaYoFXMTyj7S6ryFiTgki8Pa-2FexZSQMF7rqLvSholf8VRzqSUk9RlE4Ur1kKU16OgbmnUzumvxbyl0vsXlMGoldtE6bOdDrJ9lfpsgyIVASwtERUY3QRADUrXndmZkyW-2FeXb5dgTP3-2FadLRGmWJTM542kLeWw0fN4SSkZ12-2B0E7b2hbiYiOAcYoZvRlHU-2BbBHlFw2o9vQiICQ-2Bt73DsI9p3sDnnFo-2BWcCSeZWyJDJ1xAH5Bn-2F4u6tT-2Fl2aUVx-2FVn5Y-2FbXLvqJGOsQCbsxxf9JvNu07zoTTqvs38Qn-2FdqgWKEW15SakEfnpS0dK0Ak-2BkelqhST9XouXGGxsDe4r3VG48UfOXEn8mPJkho0YAd9UZHYFflOOcam-2BWE4pXgoIxZjkSQdUmwZKbjLWT5lxK3PQVNN2T1eG0bLkL0cL6LgC1g13OdYncFh9RhfY0CizmO7bNkBFYvugiKUKxWJ-2BCU2088mGee26xQkaOk0rPAg6J3NG2BwvIoM0r15EHqhA8I-2FIojbkKLbAfOSx3-2B9xcEvyqC0-2FBeBuTMhb9Ij6wd0tyeD-2FJ9d0kBU5lqafHlyEHPVHCbXrK8ItRDMGUwfHgsZ2s-2Fa4A9esb92HfWmDfSWJcXKRqReXH8yQNvyImEioyNCOa3er4tuDAtKx7VR-2BR3xzio4Yf0m81vkv0llm74B5UKcF6FHOvoPQ1D2YYit9wwyGg3eBwF-2BsoF96a32vIP0PgVQ3zeGG3AMmo6kf5cEmY89ffZAfVGk-2FRA8AjMzmZF2osnh1mwOqeL9Z2gUJhiICYgspY1tW8VQfKby-2BgTUmBpS8ITg7K2o3qSx2wTRTNclvE1u4XpDbNtYOOdCl8N8XwVLCzu6X-2FRW4hnaB8kOcUNYFx1mO8MgjJXUJWse7w9pWc-2BY9x9ZtYp48APGVgBMNLh4ZjVLn88Y81Iq3Y-2BzVh-2BSg4-3D)  
> 
> Thanks for creating with Unity,  
> 
> The Unity team

Итак, выделим следующие моменты, точнее - на что это влияет:

1. Unity Pro and Enterprise повысят цену на 5%. Т.е. инди-разработчики не пострадают от этого сильно. Учитывая, что для подключения подписки Pro нужно в год зарабатывать 200к бенджаминов в год - изменение цены годовой подписки на место с 2,030$ на 2,310$ просто "пук в лужу". Те кто не согласны с подобными условиями - уже как 2 года могли переучиться на Unreal Engine 5, Godot Engine и любой другой движок с более лояльным к разработчику ценообразованием
2. Unity DevOps. Эти изменения касаются средств для разработчиков, больше послаблений для бесплатных тарифов, видимо чтобы подсадить "юных подаванов" на их сервисы и получать доп плату в отрыве от лицензирования
3. Физика Havok уберут из Unity Pro и Enterprise. Да, уберут, но она все еще будет доступна как стороннее дополнение от Microsoft. Видимо юнитеки так затрахались выслушивать пользователей с ошибками Havok'а и перенаправлять их к мелкомягким - что полностью их обрубают от себя. Хотя может проблема в чем-то другом, но это уже останется за дверями компании 

Итак, что мы имеем? Инди-разработчикам переживать пока не стоит, т.к. все эти изменения касаются только больших игровых студий. Делаем игры, пьем пиво, радуемся жизни и тому что можем продолжать эти игры делать, хех.