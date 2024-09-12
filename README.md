# Hello, This is your "StaticWeb" for IEclub

## About me
![Wireframe - 1](https://github.com/user-attachments/assets/effd1cba-dff4-41ef-b4fc-38f28922fdcf)

## Contact
![Wireframe - 2](https://github.com/user-attachments/assets/59f7fe2b-3a28-44cf-933b-6e7fa6c9fb6a)

## Portfolio
![Wireframe - 3](https://github.com/user-attachments/assets/f1a11008-f7e5-46aa-b2f3-7386cc388d28)


# Preview CSS file

``` bash
body {
  background-color: #2d3142;
  color: white;
  font-family: "Poppins", system-ui;
}

h1 {
  text-transform: uppercase;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.links {
  display: flex;
  gap: 20px;
}

.links a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

.links a:hover {
  color: gray;
}

.grid-container {
  display: grid;
  grid-template-columns: 2fr 2fr;
  gap: 10 px;
}

.flex-container {
  display: flex;
  gap: 10px;
  height: 500px;
}

.div-image {
  max-width: 350px;
  min-width: 300px;
  height: full;
  /* border: 2px solid white; */
  overflow: hidden;
  border-radius: 16px;
}

.image-cover-div {
  object-fit: cover;
  width: 100%;
  height: 100%;
}

.introtext {
  margin-left: 20px;
}

.align-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.gallery {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 20px;
  justify-content: space-around;
}

.gallery-item {
  height: 300px;
  text-align: center;
  padding: 10px;
}

.gallery-item-img {
  object-fit: cover;
  width: 100%;
  height: 100%;
}
```