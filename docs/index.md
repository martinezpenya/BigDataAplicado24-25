## BigDataAplicado24-25

**UD00: Conceptos generales**

1. [ConceptosGenerales](<./UD00/1.ConceptosGenerales.md>)

2. [bash](<./UD00/2.bash.md>)

3. [EntornosVirtualesPython](<./UD00/8.EntornosVirtualesPython.md>)

**UD01: Hadoop**

**UD02: Cluster Hadoop pseudodistribuido. HDFS.**
	1. [instalacion](<./UD02/1.instalacion.md>)
	2. [webdfs](<./UD02/2.webdfs.md>)


## Test

!!!question "Ejercicios"
	agregar:

	  - admonition
      - pymdownx.details

    First, create a directory in your `docs` directory to hold the event pages:

    ```
    $ mkdir docs/events
    ```

    Then, add a file `.meta.yml` inside this new directory with settings for
    the page icon and a hot pink background color that will stand out on
    social media. Note that you can override the background image by setting it
    to `null` here since it is not visible anyway because of the opaque coloring.

    ```yaml
    ---
    icon: material/calendar-plus
    social:
      cards_layout_options:
        background_image: null
        background_color: "#ff1493"
    ---
    ```

    Now add a page within the `docs/events` directoy. It does not need to have
    any special content, just a top level header.

    To turn on the `default/variant` layout in `mkdocs.yml`, add the
    `cards_layout` option and also add the meta plugin:

    ```yaml
    plugins:
      - meta
      - social:
          cards_layout: default/variant
    ```

    After running `mkdocs build`, you can see that the social card at
    `site/assets/images/social/events/index.png` features the page icon.



> [!question] Title
> Contents




