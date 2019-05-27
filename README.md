# C-digos-de-gr-ficos
Códigos para plotagem de gráficos no Python

from matplotlib import pyplot as plt

# Taxa geral
ano = ['2003', '2004', '2005', '2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015', '2016', '2017', '2018']
tx_geral = [29.37, 28.24, 26.86, 23.37, 21.19, 20.59, 19.64, 18.22, 17.65, 17.17, 15.44, 15.32, 14.07, 12.23, 12.94, 13.74]
mt_alto = [20.0, 20.0, 20.0, 20.0, 20.0, 20.0, 20.0, 20.0, 20.0, 20.0, 20.0, 20.0, 
          20.0, 20.0, 20.0, 20.0, ]

plt.figure(figsize = (10, 4))
plt.plot(ano, tx_geral, color = 'blue', marker = ' ', linestyle = 'solid')
plt.plot(ano, mt_alto, color = 'red', marker = ' ', linestyle = '--')

plt.grid(True, color = 'grey', linestyle = ':')


# taxa menor de 15
ano = ['2003', '2004', '2005', '2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015', '2016', '2017', '2018']
tx_menor = [7.98, 7.68, 7.34, 6.22, 6.07, 5.89, 5.43, 5.36, 5.22, 4.81, 5.03, 4.88, 4.46, 3.63, 3.72, 3.75]
mto_alto = [5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, 5.0, ]

plt.figure(figsize = (10, 4))
plt.plot(ano, tx_menor, color = 'green', marker = ' ', linestyle = 'solid')
plt.plot(ano, mto_alto, color = 'red', marker = ' ', linestyle = '--')

plt.grid(True, color = 'grey', linestyle = ':')



# Gráfico taxa GIF 2
ano = ['2003', '2004', '2005', '2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015', '2016', '2017', '2018']
tx_gif2 = [14.50, 14.60, 14.20, 13.20, 13.60, 14.00, 12.70, 11.70, 11.30, 11.50, 9.90, 10.10, 9.20, 8.42, 9.39, 10.13]

plt.figure(figsize = (10, 4))
plt.plot(ano, tx_gif2, color = 'purple', marker = ' ', linestyle = 'solid')

plt.grid(True, color = 'grey', linestyle = ':')

plt.show()
