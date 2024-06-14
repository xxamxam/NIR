<table>
    <tr>
        <td align="center"> <b> Название исследуемой задачи </b> </td>
        <td> Эффективный метод скаляризации и поиска конкурентного решения без итеративных вычислений для Липшицевых функций </td>
    </tr>
    <tr>
        <td align="center"> <b> Тип научной работы </b> </td>
        <td> ВКР </td>
    </tr>
    <tr>
        <td align="center"> <b> Автор </b> </td>
        <td> Латыпов Ильгам Магданович </td>
    </tr>
    <tr>
        <td align="center"> <b> Научный руководитель </b> </td>
        <td> к.т.н. Дорн Юрий Владимирович </td>
    </tr>
</table>

## Abstract

В практических инженерных и оптимизационных приложениях решение задач многоцелевой оптимизации часто подразумевает использование методов скаляризации. Хоть известные подходы могут и быть эффективными, они часто сопряжены со значительными вычислительными затратами из-за необходимости итеративных вычислений, а также их использование усложняется необходимостью подбора гиперпараметров.
В этой работе предлагается переопределить понятие конкурентного решения, чтобы получить интерпретируемый метод скаляризации, не требующий настройки гиперпараметров. Для предложенного метода скаляризации предлагается способ получения приближенного решения в случае, когда функции липшицевы и их вычисление возможно только один раз. Это актуально, когда вычисления очень дорогие или повторное вычисление невозможно.
Вычислительные эксперименты, проведенные для задачи конкурирующих потоков минимальной цены, демонстрируют работоспособность и масштабируемость предложенного подхода, подчеркивая его потенциал для решения вычислительных проблем в MOO в различных областях.

## Repository Structure

The repository is structured as follows:

- `paper`: This directory contains the main paper in PDF format (`diploma_text.pdf`) 
<!-- and the LaTeX source files in paper/source. -->
- `code`: This directory contains the code used in the paper. 
<!-- It has its own `README.md` file providing a detailed description of the code files. -->

# Установка

Чтобы повторить результаты вычислительного эксперимента, рекомендуется установить все необходимые зависимости.
Файл ``requirements.txt`` находится в директории ``code``.
Для установки

- Сделайте ``git clone`` этого репозитория.
- Создайте новое ``conda`` окружение и активируйте его.
- Запустите ``pip install -r requirements.txt``.
