export default async function handler(req, res) {
  res.setHeader('Access-Control-Allow-Origin', '*');
  res.setHeader('Access-Control-Allow-Methods', 'GET');
  
  const CSV_URL = "https://docs.google.com/spreadsheets/d/e/2PACX-1vTRf5d6go2G1q8zxRwn2ESFYAJDQPLQf-nvODCVt0f-1jfjheYTISyvUr7RQyBzjJ8Voy6CNo51thSu/pub?gid=2107794426&single=true&output=csv";
  
  try {
    const response = await fetch(CSV_URL);
    if (!response.ok) throw new Error('HTTP ' + response.status);
    const text = await response.text();
    res.setHeader('Content-Type', 'text/plain; charset=utf-8');
    res.status(200).send(text);
  } catch (err) {
    res.status(500).json({ error: err.message });
  }
}
