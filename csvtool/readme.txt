------------------------------------------------------------------------

CsvTool - Manages csv files

Commands:

    * about
          o Displays information on various topics
    * append
          o Appends one csv file after another.
    * cd
          o Change delimeter.
    * charset
          o shows character encodings
    * delta
          o Will produce a csv with n - 1 records, and with one more
            column with a delta value.
    * diff
          o Produces a csv with the diff of two csv:s
    * dir
          o Lists the files in the current directory
    * dropColumn
          o Drops a column from a given csv
    * enum
          o Adds a column that enumerates the records.
    * groupBy
          o Groups by a set of columns and adds a count column.
    * gui
          o Displays a gui with a grid with the csv.
    * help
          o Displays help on various commands.
    * in
          o Returns records where value of a column are found (or not
            found) in another csv
    * join
          o Joins two CSVs into one using an expression
    * metadata
          o Creates a csv with metadata of given csv
    * mod
          o Modifies values of a column.
    * move
          o Moves a column to be first column in csv
    * select
          o Returns a subset of csv that evaluates to true on
            expression
    * serve
          o Starts a http-rest service to manipulate a csv
    * sort
          o Sorts the csv based on the given column
    * toExcel
          o Produces an excel file based on the given csv file.
    * toHtml
          o Exports a csv to html.
    * toInsertStatements
          o Creates sql insert statements for each record of the input
            csv.
    * toXML
          o Exports a csv to xml.
    * transpose
          o Transposes a csv. Useful when there are many columns and
            few lines.
    * view
          o Displays a csv more human friendly. Useful together with
            'less -S'

Authors:

    * Daniel Schwartz, schw@rtz.se
------------------------------------------------------------------------
