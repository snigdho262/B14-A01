.spot{
    padding: 50px;
}

.spot h2{
    text-align: center;
    font-size: 48px;
    margin-bottom: 5px;
}

.spot > p{
    text-align: center;
    color: gray;
    margin-bottom: 25px;
}


.pricing-cards{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}


.standard,
.pro,
.team{
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 32px;
}
.pricing{
    color:#888888;
}

.pro{
    background: #0F172A;
    color: white;
}


.standard h4,
.pro h4,
.team h4{
    font-size: 44px;
    margin: 10px 0;
}


.standard ul,
.pro ul,
.team ul{
    margin: 20px 0;
    padding-left: 20px;
}

.standard li,
.pro li,
.team li{
    margin: 10px 0;
}

/* Button */

.standard-btn{
    width: 100%;
    padding: 12px;
    border: 1px solid blue;
    border-radius: 8px;
    background: white;
    color: blue;
    cursor: pointer;
}

.pro .standard-btn{
    background: blue;
    color: white;
    border: none;
}


/* @media (max-width:768px){

    .pricing-cards{
        grid-template-columns: 1fr;
    }

} */