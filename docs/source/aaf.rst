.. _aaf-label:

Australian Access Federation
============================

What is the AAF?
----------------

The Australian Access Federation (AAF) is an identity broker. It enables access to online resources for the Education and Research sector by providing subscribers with a national single sign-on that allows individuals across many different organisations to collaborate and access online resources within a trusted environment. AAF subscriber base includes:

- all Australian Universities
- CSIRO and other government research agencies as well as leading research support organisations
- organisations providing online products or services for teaching, learning and research.

You can find more details on https://aaf.edu.au/about/ and  a brief overview about AAF in this video:

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/jJd-bu1HYbc"
                frameborder="0" allowfullscreen
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
        </iframe>
    </div>
    <br/>


Store.Monash New Authentication Mechanisms
------------------------------------------

Store.Monash now supports three authentication mechanisms:

- Monash Identity (previously know as Authcate) 
- Australian Access Federation
- Google Authentication (Restricted Access)

We will gradually phase out the direct authentication against the Monash Identity (Authcate) by moving all the accounts to the Australian Access Federation (AAF) as the main authentication mechanism. During this transition phase, Monash users can still use their Monash username and password to access Store.Monash if they prefer to do this.   

Users who cannot use AAF because their organization is not an AAF subscriber can use Google Authentication. This will need an additional admin approval and will be restricted to specific use cases.  


Store.Monash Account Migration
------------------------------

For current Store.Monash users, we built an account migration functionality to facilitate their transition to AAF. The migration functionality moves their Store.Monash settings and data from their Authcate account to their AAF account. The process is very simple and does not include copying your data. It just changes the ownership of your data from your Authcate account to your AAF account. After the completion of this process, you will not be able to use your Authcate account to access Store.Monash. 

See:

- :ref:`aaf-migration-label`
- :ref:`google-migration-label`

