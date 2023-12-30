# Centroids
Обычно под центроидом множества в метрическом пространстве понимается центр масс.  
Однако существует большое количество возможных определений центра фигуры или множества точек как  
representation object. 
Например для полигона мы можем определить:
- Mass center of lamina
- Centroid of perimeter
- Mass center of vertices
и в общем случае они будут различны [ноутбук]()

Чаще всего в основе определения лежат понятия mean, equality, ...  
Кратко опишем возможные подходы к определению центров.  

## Количество
- Центр масс может быть только один
- Centroidal Voronoi diagram не только может иметь несколько seeds, но и расположены они могут быть по-разному  

Субъективно, due to [capacity of short-term memory](https://elifesciences.org/articles/22225)  
не более 10 (чаще не более 7) items воспринимаются как индивидуальные.   
Большее количество наш мозг воспринимает статистически.  
Для равномерного распределения по множеству большого количества центров  
существуют специальные методы
- Low - discrepancy sequences
- Poisson Disk
- Hyperuniformity
- Equal area



## Расположение и возможность определения
- Центр масс может лежать вне фигуры (и не принадлежать множеству точек)
- Для графа такой центр невозможно определить
- medoids are always restricted to be members of the data set
- В случае таких объектов как строки мы можем определить [расстояния между ними](https://en.wikipedia.org/wiki/String_metric),
но можно ли ввести "центр"?

## Способы определения
### Using metric distance
1. Medoid or centroid
2. All or subset
3. Goal function
   
### Using [graph measures](https://en.wikipedia.org/wiki/Centrality)

### Some different approaches
1. Lloyd relaxation
2. Circles packing
3. [Reference circles](https://www.taylor-hobson.com/resource-center/faq/what-reference-circles-are-there)
4. Light wave method

## Example of special center
В этом ноутбуке рассматривается не встречавшееся мне ранее определение центра фигуры или множества точек,
основанное на минимизации разброса расстояний до границы.






