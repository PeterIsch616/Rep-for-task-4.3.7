# Rep-for-task-4.3.7
trial repository
font-family: Schwabacher;
    src: url("fonts/Schwabacher/Schwabacher font.ttf");
}

body {
    background-color: #77a79f;
}

.dropdown {
    margin: 62px 84px 0px 77px;
    width: 500px;
    font-family: Schwabacher;
    font-style: normal;
    font-weight: normal;
    color: #000;
    box-sizing: border-box;
}

.dropdown-container {
    display: flex;
    flex-direction: column;
    min-height: 326px;
}

.dropdown input {
    border: none;
    font-size: 48px;
    line-height: 56px;
    width: 100%;
    background-color: #FFFFFF;
    box-sizing: border-box;
}

.dropdown-content {
    width: 100%;
    cursor: pointer;
    font-size: 30px;
    line-height: 35px;
    border: 2px solid #000;
    box-sizing: border-box;
    background-color: #c2b4b1;
}

.dropdown-content:hover {
    background-color: #4cc9a9;
    cursor: pointer;
}

.chosens {
    display: flex;
    flex-direction: column;
    top: 326px;
    width: 503px;
}

.chosen {
    display: flex;
    text-align: left;
    vertical-align: middle;
    font-size: 24px;
    padding: 8px 16px;
    line-height: 28px;
    border: 1px solid #000;
    background-color: #41a1ad;
}

.btn-close {
    margin-left: auto;
    margin-top: auto;
    margin-bottom: auto;
    background-repeat: no-repeat;
    background-image: url("img/Cross.png");
    background-color: transparent;
    background-size: contain;
    outline: none;
    border: none;
    cursor: pointer;
    width: 42px;
    height: 38.5px;
    right: 17px;
}
