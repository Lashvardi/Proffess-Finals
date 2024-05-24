## პროფესიული ჯგუფების ფინალური პროექტების ვარიაციები

```
რამოდენიმე პროექტი მოითხოვს PROXY სერვერს
რომელიც შეგიძლიათ იპოვოთ ამ ბმულზე
https://github.com/Lashvardi/small-proxy-server
```
### პროექტები
```
პირველი პროექტი
🔴 საჭიროა PROXY
```
მოიცავს სკოლების საძიებო სისტემას საქართველოს მასშტაბით

- https://skolebi.emis.ge/back/school/generaldata
- - აბრუნებს ზოგად მონაცემებს რამდენი სკოლაა საქართველოს მასშტაბით
- https://skolebi.emis.ge/back/educationinfo
- - აბრუნებს ზოგად ინფორმაციას რას გვაძლევს სკოლა (სტატიების სია)
- https://skolebi.emis.ge/back/school/regionschoolcount
- - სკოლები რეგიონების მიხედვით სია (ქარდებში შეგვიძლია გავიტანოთ)
- https://skolebi.emis.ge/back/school/region
- - რეგიონების ჩამონათვალი ფილტრაციისთვის
- https://skolebi.emis.ge/back/school?page=1&size=10&search=(სკოლის სახელი) მაგ: 162
- - აბრუნებს სკოლის მწირე ინფორმაციას თუმცაღა მოყვება Id რის მეშვეობითაც შეგვიძლია რო წამოვიღოთ მთლიანი ინფორმაცია სკოლის შესახებ (schoolId) ამ პარამეტრით
- https://skolebi.emis.ge/back/school/search/1463
- - სკოლის დეტალური ინფორმაციის წამოსაღებად საჭიროა ეს მისამართი
- https://skolebi.emis.ge/back/school/search?page=1&size=24&regions=1009
- -რეგიონის მიხედვით სკოლების წამოღება. ვატანთ რეგიონის აიდის.



```
მოცემულ პროექტში ფოტოს ჩასმის ინსტრუქცია
სკოლის დეტალური ინფორმაციის წამოღებისას მოყვება   "imageAttachmentId": 16368
რომელიც უნდა მოვათავსოთ ლინკში
https://skolebi.emis.ge/back/imagedownload?attachmentId=(აიდი)
```
