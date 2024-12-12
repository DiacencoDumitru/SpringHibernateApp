#### Spring приложение с Hibernate
* Свяжем наше Spring приложение с Hibernate.
* Добавим `@PropertySource` для hibernate
* Так-же для транзакций `@EnableTransactionManagement`
* Внедряем Environment, для SpringConfig что-бы мы могли получить доступ к ключ-значение конфигурационного файла `hibernate.properties`
* Реализуем метод index()
* @Transactional