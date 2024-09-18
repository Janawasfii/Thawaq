Thawaq is an online platform for rating restaurants and cafes. It features three types of users. The first is the admin of the store, whether it is a restaurant or a café, responsible for managing store data by adding menus, branches, and all relevant details. Services are made available to the admin after the data is reviewed and verified. The second user is the expert, who can provide reviews and ratings for stores, as well as receive review requests from stores, which they can either accept or decline. Expert reviews are more credible and appear in special lists dedicated to expert reviewers.

The third type of user is the customer, who can view all store ratings, whether from experts or other customers. Customers can also rate the restaurant based on their experience, evaluating cleanliness, service, quality, and cost. Additionally, they can "like" any product from the restaurant's menu that they are reviewing.

To ensure that customers find the best possible stores based on their preferences, the platform offers more than 30 filtering options for browsing stores. The site is highly reliable, as experts cannot provide reviews or accept requests without prior verification of their expertise and knowledge. Moreover, the platform includes a recommendation system for customers, suggesting products based on their preferences.
From a technical perspective, the platform has been built using the Spring Boot framework, connected to a MySQL database. It has been effectively secured and thoroughly tested to ensure quality.

The system comprises a total of 12 entities, including four types of users, and features more than 100 endpoints to serve users and ensure that all requirements are met comprehensively.





ذواق هو منصة إلكترونية لتقييم المطاعم والمقاهي، وتضم ثلاثة أنواع من المستخدمين. النوع الأول هو مدير المتجر، سواء كان مطعمًا أو مقهى، وهو المسؤول عن إدارة بيانات المتجر من خلال إضافة قوائم الطعام والفروع وكل التفاصيل ذات الصلة. تُتاح الخدمات للمدير بعد مراجعة البيانات والتحقق منها. النوع الثاني هو الخبير، الذي يمكنه تقديم المراجعات والتقييمات للمتاجر، بالإضافة إلى استقبال طلبات المراجعة من المتاجر والتي يمكنه قبولها أو رفضها. تُعد مراجعات الخبراء أكثر مصداقية وتظهر في قوائم خاصة مخصصة لهم.

النوع الثالث من المستخدمين هو العميل، الذي يمكنه عرض جميع تقييمات المتاجر سواء من الخبراء أو العملاء الآخرين. يمكن للعملاء أيضًا تقييم المطاعم بناءً على تجربتهم، وتقييم النظافة، والخدمة، والجودة، والتكلفة. بالإضافة إلى ذلك، يمكنهم "الإعجاب" بأي منتج من قائمة الطعام أثناء تقديمهم للمراجعة.

لضمان أن يجد العملاء أفضل المتاجر التي تناسب تفضيلاتهم، توفر المنصة أكثر من 30 خيارًا للتصفية لتصفح المتاجر. يعتبر الموقع موثوقًا للغاية، حيث لا يمكن للخبراء تقديم المراجعات أو قبول الطلبات دون التحقق المسبق من خبراتهم ومعرفتهم. علاوة على ذلك، تتضمن المنصة نظام توصيات للعملاء يقترح المنتجات بناءً على تفضيلاتهم.
من الناحية التقنية، تم بناء المنصة باستخدام إطار عمل Spring Boot، وهي متصلة بقاعدة بيانات MySQL. تم تأمينها بفعالية واختبارها بشكل شامل لضمان الجودة.يتكون النظام من 12 كيانًا، بما في ذلك أربعة أنواع من المستخدمين، ويحتوي على أكثر من 100 نقطة نهاية لخدمة المستخدمين وضمان تلبية جميع المتطلبات بشكل شامل.




<img width="740" alt="Thawaq Use Case Diagram" src="https://github.com/user-attachments/assets/430a89b3-35aa-41ad-bbe7-c5974e0d2dee">




![3f286489-472e-4cf7-98e0-dc1a11b43fd7](https://github.com/user-attachments/assets/13badc79-7c1f-4ff5-951b-6eacfc492cf8)



https://documenter.getpostman.com/view/37199310/2sAXqqchcn

https://slidesgo.com/editor/share/9d075d96-f625-4459-a91b-c2c51fe8c9c5?embed=0&expires=1726721384&signature=55c3fae6a22ebf4e67cf248a909d8c38973e571ed826490ecb7f34b64ba492a3#rs=link

https://www.figma.com/design/1CZxolWa71YlKEo5zow0jI/Thawaq?node-id=0-1&t=ZMWrqEWQNURWh0N8-1

My Endpoints:
-applyDiscountToCategoryByName</br>
-findDishesByPriceRange</br>
-getAllRatings</br>
-getMyRatingForClient</br>
-getMyRatingForExpert</br>
-addRatingToStore</br>
-addRatingFromExpertToStore</br>
-CalculateAverageServiceStore</br>
-getTop4CafesByAverageRating</br>
-getTop4RestaurantByAverageRating</br>
-getMyRequestForExpert</br>
-findStoreByTypeOfActivity</br>
-getBestServiceForCafesByName</br>
-getBestServiceForRestaurantByName</br>
-getBestServiceForBothByName</br>
-getBestServiceForCafesByCategoryName</br>
-getBestServiceForRestaurantByCategoryName</br>
-getBestServiceForBothByCategoryName</br>
-getBestServiceForCafeByCityName</br>
-getBestServiceForRestaurantByCityName</br>
-getBestServiceForBothByCityName</br>
-activateStoreAdmin</br>
-deactivateStoreAdmin</br>

The Model : Rating and Request </br>
The CRUD: Rating and Request </br>



