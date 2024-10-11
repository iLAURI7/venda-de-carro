<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venda seu carro</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <h3>Cadastre seu veículo para vender mais rápido!</h3>
        </div>
        <div class="form-container">
            <div class="form-header">
                <p>Formulário</p>
            </div>
            <div class="form-body">
                <h1 class="from-title">Venda fácil seu carro!</h1>
                <p>
                    Descreva as características e marque os opcionais que ele possui:
                </p>
                <form>
                    <div class="box-input">
                        <label for="title">
                            Título do anúncio <span class="required-field">*</span></label>
                            <input 
                            type="text"
                            name="title"
                            id="title"
                            class="block"
                            placeholder="Título para o anuncio"
                            minlength="1"
                            maxlength="20"
                            required
                            />
                    </div>
                    <div class="box-input">
                        <label for="price">
                            Preço <span class="required-field">*</span></label>
                            <input 
                            type="number"
                            name="price"
                            id="price"
                            class="block"
                            placeholder="Defina o preço"
                            required
                            />
                    </div>
                    <div class="box-input">
                        <label for="price">
                            Descrição <span class="required-field">*</span></label>
                            <textarea name="description" id="description" class="block" placeholder="Aqui você coloca os detalhes do veículos, por exemplo: se ele tem algum arranhão"></textarea>
                         <div class="box-input">
                        <label for="brand">
                            Marca <span class="required-field">*</span></label>
                            <input 
                            type="text"
                            name="brand"
                            id="brand"
                            class="block"
                            placeholder="Digite a marca do veículo"
                            required
                            />
                    </div>
                    <div class="box-input">
                        <label for="model">
                            Modelo <span class="required-field">*</span></label>
                            <input 
                            type="text"
                            name="model"
                            id="model"
                            class="block"
                            placeholder="Digite o modelo do veículo"
                            required
                            />
                    </div>
                    <div class="box-input">
                        <label for="mileage">
                            Kilometragem <span class="required-field">*</span></label>
                            <input 
                            type="number"
                            name="mileage"
                            id="mileage"
                            class="block"
                            placeholder="Digite a kilometragem do veículo"
                            required
                            />
                    </div>
                    <div class="box-input">
                        <label for="purchase_date">
                            Data de compra <span class="required-field">*</span></label>
                            <input 
                            type="date"
                            name="purchase_date"
                            id="purchase_date"
                            class="block"                            
                            required
                            />
                    </div>
                        <div class="box-input">
                        <p>Tipo de câmbio <span class="required-field">*</span></p>
                           <input type="radio" id="manual" name="gear">
                           <label for="manual">Manual</label>
                           <input type="radio" id="auto" name="gear">
                           <label for="manual">Automático</label>
                    </div>
                        <div class="optinal-box">
                        <p>Opcionais</p>
                           <ul class="optional-list">
                            <li>
                                <input type="checkbox" id="airbag" name="optional []" value="airbag">
                                <label for="airbag">Airbag</label>
                            </li>
                            <li>
                                <input type="checkbox" id="alarm" name="optional []" value="alarm">
                                <label for="alarm">Alarme</label>
                            </li>
                            <li>
                                <input type="checkbox" id="ac" name="optional []" value="ac">
                                <label for="ac">Ar Condicionado</label>
                            </li>
                            <li>
                                <input type="checkbox" id="reverse_camera" name="optional []" value="reverse_camera">
                                <label for="reverse_camera">Câmera de Ré</label>
                            </li>
                           </ul>
                    </div>
                    <div class="optinal-box">
                           <ul class="optional-list">
                            <li>
                                <input type="checkbox" id="lane_assist" name="optional []" value="lane_assist">
                                <label for="lane_assist">Assistente de Pista</label>
                            </li>
                            <li>
                                <input type="checkbox" id="keyless" name="optional []" value="keyless">
                                <label for="keyless">Partida Keylass</label>
                            </li>
                            <li>
                                <input type="checkbox" id="smartphone" name="optional []" value="smartphone">
                                <label for="smartphone">Integração com Celular</label>
                            </li>
                            <li>
                                <input type="checkbox" id="leather_seat" name="optional []" value="leather_seat">
                                <label for="leather_seat">Banco de Couro</label>
                            </li>
                           </ul>
                    </div>
                    <div class="box-input">
                        <p>Fotos do carro: <span class="required-field">*</span></p>
                        <input type="file" multiple accept="image/png, image/jpg" id="images" name="images" required>
                    </div>
                        <input type="submit" value="Enviar" class="btn-submit" />
                </form>
            </div>
         </div>
    </div>
</body>
</html>
