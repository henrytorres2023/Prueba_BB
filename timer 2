import time
from pybit.unified_trading import HTTP

session = HTTP(
    api_key="Dq8cUaoBhxBNecloNV",
    api_secret="iAwmpdGPiaCGSpz16AonbBXTweF7OX1n3fE5",
    recv_window=5000
)

server_time = session.get_server_time()["time"]
local_time = int(time.time() * 1000)
dif = (server_time - local_time)/1000
print(f"Hora del servidor: {server_time}, Hora local: {local_time}")
print(f"Diferencia en segundos: {dif}")
