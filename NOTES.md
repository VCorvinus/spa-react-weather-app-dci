const url = 'https://wft-geo-db.p.rapidapi.com/v1/geo/cities';
const options = {
	method: 'GET',
	headers: {
		'X-RapidAPI-Key': 'c2b46f0abemsh89395de9518b15ap14d257jsnb83178df9de6',
		'X-RapidAPI-Host': 'wft-geo-db.p.rapidapi.com'
	}
};

try {
	const response = await fetch(url, options);
	const result = await response.text();
	console.log(result);
} catch (error) {
	console.error(error);
}



28ff0e2cae2cbb9fcd1eb365846ce579


npm i react-accessible-accordion

npm i react-select-async-paginate --force