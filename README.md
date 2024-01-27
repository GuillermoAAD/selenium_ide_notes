# selenium_ide_notes

![Selenium IDE](https://www.selenium.dev/selenium-ide/img/selenium-ide64.png)

My personal Selenium IDE notes.

---



<!--- ####### INDEX ####### --->
**Index**
1. [VALIDATIONS](#validations)
    - [Number](#number)
        - [Range](#range)
    - [Date](#date)
        - [From today](#date-from-today)
        - [Formats](#formats)
2. [REGEX](#regex)
3. [COMPARISON](#comparison)
4. [LOOPS](#loops)
    - [TIMES](#times)
    - [~~TIMES nested~~](#times-nested)
    - [DO...REPEAT IF nested](#dorepeat-if-nested)
    - [DO...REPEAT IF nested in TIMES](#dorepeat-if-nested-in-times)



[⬆](#)
<!--- ####### START - VALIDATIONS ####### --->
## VALIDATIONS 

### Number 

-  #### Range
    Validate that the given number is within the range.

    ```js
    return Number(${my_num}) > 0 && Number(${my_num}) < 123;
    ```

### Date
- #### Date from today
    Validate that the given date is greater than or equal to the current date.

    ```js
    return ${my_date_formatted} >= ${today_date};
    ```

- #### Formats
    Examples to format the date in JS format

    ```js
    // Example: Jan/17/2024

    return new Date(${my_date}.replace(/(\w+)\/(\d+)\/(\d+)/, '$1 $2, $3'));
    ```

<!--- ####### END - VALIDATIONS ####### --->

[⬆](#)

<!--- ####### START - REGEX ####### --->
## REGEX 

REGEX text


<!--- ####### END - REGEX ####### --->

[⬆](#)

<!--- ####### START - COMPARISON ####### --->
## COMPARISON 

COMPARISON text

<!--- ####### END - COMPARISON ####### --->

[⬆](#)

<!--- ####### START - LOOPS ####### --->
## LOOPS 

<!--- --->
- ### TIMES
    
    Example of how to use the ***times*** loop.
    <!-- //TODO: Add image with example -->
    ![Times](resources/loops/times.pngg)

<!--- --->
- ### ~~TIMES nested~~
    
    Example of how the ***times*** loop should be used. But there is a bug that does not allow the correct use of this functionality.

    <!-- //TODO: Add image with example -->
    ![Times nested](resources/loops/times_nested.png)

<!--- --->
- ### DO...REPEAT IF nested
    Example of how to use the ***do...repeat if*** loop.

    <!-- //TODO: Add image with example -->
    ![Do...repeat if](resources/loops/do_repeat_if.png)

<!--- --->
- ### DO...REPEAT IF nested in TIMES
    
    Example of how to use the ***times*** loop.
    <!-- //TODO: Add image with example -->
    ![Do...repeat if nested in times](resources/loops/do_repeat_if_nested_in_times.png)

<!--- ####### END - LOOPS ####### --->

[⬆](#)