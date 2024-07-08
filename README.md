# Altium_JLCPCB

JLCPCB design rules and stackups for Altium Designer.

Design rules
------------

  - 2 layer
    - 1 oz copper
      - 5mil trace width & clearance
      - 0.3mm min. hole diameter
      - 0.5mm min. via diameter
      - 0.254mm hole clearance
    - 2 oz copper
      - 8mil trace width & clearance
      - 0.3mm min. hole diameter
      - 0.5mm min. via diameter
      - 0.245mm hole clearance
  - 4 layer
    - 1 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 3.5mil trace width & clearance on all layers
      - 0.2mm min. hole diameter
      - 0.35mm min. via diameter (from note 1 and 2)
      - 5mil via clearance
      - 0.254mm hole clearance
    - 2 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 3.5mil trace width & clearance on mid layers
      - 8mil trace width & clearance on top & bottom layers
      - 0.2mm min. hole diameter
      - 0.4mm min. via diameter (from note 1)
      - 0.254mm via clearance
      - 0.254mm hole clearance
  - 6 layers
    - 1 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 3.5mil trace width & clearance on all layers
      - 0.2mm min. hole diameter
      - 0.35mm min. via diameter
      - 0.254mm via clearance
      - 0.254mm hole clearance
    - 2 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 3.5mil trace width & clearance on mid layers
      - 8mil trace width & clearance on top & bottom layers
      - 0.2mm min. hole diameter
      - 0.35mm min. via diameter (from note 1 and 2)
      - 0.254mm via clearance
      - 0.245mm hole clearance

All design rules include a `PowerPads` pad class for easy direct polygon pour connection.


References
----------

  - https://jlcpcb.com/capabilities/Capabilities