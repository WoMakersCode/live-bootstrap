.calculator {
	padding: 10px;
	margin-top: 20px;
	background-color: #ccc;
	border-radius: 5px;
	/*this is to remove space between divs that are inline-block*/
	font-size: 0;
}

.calculator > input[type=text] {
	width: 100%;	
	height: 50px;	
	border: none;
	background-color: #eee;	
	text-align: right;
	font-size: 30px;
	padding-right: 10px;
}

.calculator .linha { 
	margin-top: 10px;
}

.calculator .key {
	width: 78.7px;
	display: inline-block;
	background-color: black;
	color: white;
	font-size: 1rem;
	margin-right: 5px;
	border-radius: 5px;
	height: 50px;
    border: 0;
	line-height: 50px;
	text-align: center;
}

.calculator .key:hover{
	cursor: pointer;
}

.key.last{
	margin-right: 0px;
} 

.key.action {
	background-color: #646060;
}

#historico {
    margin: 0;
    padding: 15px 0 0 0;
    list-style: none;
    font-size: 12px;
}
