<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

```bash
cd ~/proyectos
```
```bash
git clone https://github.com/IFC303/myapp
```
```bash
cd myapp
```
```bash
docker run --rm -v $(pwd):/app composer install
```
```bash
cp .env.example .env
```
```bash
sudo chown -R $USER:$USER .
```
```bash
docker-compose up -d
```