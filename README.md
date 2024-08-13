run this command to install libraries:
pip install -r requirements.txt

the highlighted_countries, puppet_states and alliance_to_show can be hashed out to not use their functionalities.
example:
create_map(
    52, 19,
    highlighted_countries=['Poland'],
    puppet_states=['Germany', 'Ukraine'],
    alliance_to_show='Einheitspakt',
    output_svg='Polando.svg'
)

the results may need fixing in some svg editing software as errors may occur

Known issues:
1. countries and territories located near the edge of the image may have issues regarding their infill, solution is to edit them in svg editing software by moving path endpoints far out of the globe
