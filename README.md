# CLOSE AI

Yeslamov Temirlan 22200836
Zholdas Aldanbergen 22211514
Azamat Galidenov 22211179
Muzna Maryam 22212054
Mariia Peskova 22204195
Azbabanu Engineer 22201128
Aleksandr Nikonorov 22207162


https://mygit.th-deg.de/ainb_24_close_ai

You can see 3 repositories:
1) test is dockerize repository where docker compose file is located and other two repositories are imported as submodules
2) titanic_model_service is backend
3) titanic_web_service is frontend

To run the project:

```
cd test
docker login registry.mygit.th-deg.de
docker compose up
```

This should download two images from the container registry
The website will be accessible on port 8080