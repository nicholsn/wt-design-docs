.. _compose:

Compose: Creating New Tales
===========================

The **Compose** page allows you to create new tales that can be executed and 
shared with others. Creating a tale can be done in three steps:

  1. Name the Tale
  2. Select an Environment
  3. Select your data

.. _environment-section:

Environments
------------
On the right hand side of the screen there is a list of environments that
have programming frontends inside. For example, the **RStudio** Environment
is bundled with RStudio while the **Jupyter Notebook** Environment is bundled
with Python and Jupyter Notebook. You'll want to pick the appropriate
Environment that supports the language that you're working in.

Provided Environments
^^^^^^^^^^^^^^^^^^^^^
Whole Tale provides a number of pre-build environments for convenience. To
create your own environment, refer to the documentation page on the page for
`creating environments`_.

  1. **RStudio**: Contains RStudio with R 3.4.1
  2. **Jupyter Notebook**: Contains Jupyter Notebook with Python 
  3. **Jupyter with Spark**: Jupyter Notebook bundled with Apache Spark
  
To find more information about an environment, click the blue info icon next
to the Environment's name.

Selecting an Environment
^^^^^^^^^^^^^^^^^^^^^^^^
To select an Environment that's right for you, mouse over and select
the Environment. You'll see the Environment appear under the Tale name, seen 
below.

.. figure:: images/compose/selected_environment.png
     :align: center
     :scale: 60%
     Once an Environment is selected, it should appear under the Tale name.

.. _data-section:

Data
----
Adding Data
^^^^^^^^^^^
The data browser in the lower right hand side is used to add data to your tale.
You can add data from the both the **Data** and **Home** folders by clicking on
either and selecting data inside. You can confirm that the data has been added
by scanning the **Input data** field below the Environment. As you select files,
they'll be added to the list. A complete tale with data can be seen below.

.. figure:: images/compose/full_tale.png
     :align: center
     :scale: 60%
     A tale that is ready to be launched should include a name, Environment, 
     and data.
     
.. _launching-section:

Launching the Tale
---------
After you have finalized your tale and click `Launch New Tale`, you'll be brought
to the **Run** page where it will start up, seen in the image below. From here
you can access the tale, along with an assortment of other actions that are
documented on the `run page`_.

.. figure:: images/compose/tale_launching.png
     :align: center
     :scale: 60%
     A tale that is being created and configured.

.. _creating environments: environments.html
.. _run page: run.html